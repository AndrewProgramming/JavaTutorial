## Comments in Java Code

Comments help programmer better understand what the code is really doing. They are not programming statements and thus are ignored by the compiler.

The bold characters in the following listing are comments.

> ```java
> /** 
>  * The HelloWorldApp class implements an application that
>  * simply displays "Hello World!" to the standard output.
>  */
> class HelloWorldApp {
>     public static void main(String[] args) {
>         System.out.println("Hello World!"); //Display the string.
>     }
> }
> ```

The Java language supports three kinds of comments:

- `/* text */`

  The compiler ignores everything from `/*` to `*/`.

- `/* documentation */`

  This indicates a documentation comment (*doc comment*, for short). The compiler ignores this kind of comment, just like it ignores comments that use `/*` and `*/`. The JDK `javadoc` tool uses doc comments when preparing automatically generated documentation.

- `// text`

  The compiler ignores everything from `//` to the end of the line.