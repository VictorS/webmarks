## Input

### Using Scanner for stdin
```
Scanner scanner = new Scanner(System.in);
int n = scanner.nextInt();
String myString = scanner.next();
scanner.skip("(\r\n|[\n\r\u2028\u2029\u0085])?");
String s = scan.nextLine();
scanner.close();
```

### Using Reader for stdin
```
BufferedReader bufferedReader = new BufferedReader(new InputStreamReader(System.in));
int n = Integer.parseInt(bufferedReader.readLine().trim());
```
