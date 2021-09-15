1.资源关闭 try-catch-finaly,try-with-resourses

   static String readFirstLineFromFile(String path) throws IOException {
       try (BufferedReader br = new BufferedReader(new FileReader(path))) {
       return br.readLine();
 } 
}    