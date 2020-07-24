# JetBrains Academy HyperSkill Java Developer
<p>Link: <link>https://hyperskill.org/curriculum</link></p>

## I. Introduction to Java

<p><b>Key Feture:</b> Platform independence "Write once, Run anywhere"</p>
<p><b>Used:</b> Android, Finacial Service Industry, Telecomunication, Embedded Systems, Medical Applications.</p>
<p><b>Java has:</b> Garbage Collector-> Automatic cleans the memory from unused ubjects during runtime.</p>
<p><b>Primary </b> an imperativ language based on OOP concepts: almost every part of the program is an object. U can say it's a full interaction between objects.</p>
<p><b>Support Modern Programming Paradigms:</b></p>
<ul>
  <li>Generic Programming</li>
  <li>Concurrent Programming</li>
  <li>Functional Programming</li>
</ul>


## II. Literals
<p>Values of different datatypes are called <b>literals</b>.</p>
<p><b>Integer Literals</b></p>
<p>0, 1, 3, 10, 1000, 1500</p>
<p>For more readability we an use ' _ ' symbol. <b>Example:</b> 1000235745 -> 1_000_235_745</p>
<hr>
<p><b>Character Literals</b></p>
<p>A single character represent a letter , a number, a symbol using a <b>Single Quote</b> 'A', 'C', '7', '!', '$', " ", '_'.</p>
<p>Don't confuse <b>7</b> with <b>'7'</b> those are not the same.</p>
<p>A Character can't include 2 or more digits, letters, symbols because it represent only one Character.</p>
<p><b>Incorrect Character Liteals:</b> '123', 'abc'</p>
<hr>
<p><b>String Literls</b></p>
<p>Sequence of Characters. They represent text information.</p>
<p>To Write a String we use <b>Double Quotes</b> " "</p>
<p>"Text I want to learn Java."</p>
<hr>
<p><b>!!Remeber!!</p></b>
<p>Do not confuse literals.</p>
<p>123 is Integer || "123" is String</p>
<p>'A' is Char || "A" is String</p>
<p>'1' is Char || 1 is Integer</p>
<hr>
  
## III. Overview of the basic program
<p><b>Hello World</b></p>
<pre><code>
class Main{
    public static void main(String [] args){
        System.out.println("Hello, Tony!");
    }
} </code></pre>

<p><b>Basic Terminology:</b></p>
<p><b>Program:</b> a sequence of instructions called "Statements" executed one by one, in order from top to bot.</p>
<p><b>Statement:</b> a single action terminated by a ;</p>
<p><b>Block:</b> a group of 0 or more statements enclosed by {...}.</p>
<p><b>Method:</b> a sequence of staments that represent a high-level operation(known as subprogram or procedure).</p>
<p><b>Syntax:</b> a set of rules that define how the program should be writed.</p>
<p><b>Keywords:</b> a word that have a specific meaning in the programming language(public, class). Can't be used as names for variables or functions.</p>
<p><b>Identifier:</b> a word that refer to something in the program(such as variable name or function name).</p>
<p><b>Comment:</b> a textual explanation of what code does. Comments are ignored at runtine. Comments start with // single-line</p>
<p><b>WhiteSpace:</b> all characters that are not visible(space, tab, newline).</p>
<hr>

## III.1 The HelloWorld Program under the Microscope
<pre><code>
class Main{
    public static void main(String [] args){
        System.out.println("Hello, Tony!");
    }
} </code></pre>
<p><b>1. public class</b></p>
<p>It's the basic unit of program. Every Java program must have at least one class.</p>
<p>A <b>class</b> can have any name <code>'App'</code>, 'Main', 'Program' but it must not start with  a digit.</p>
<p>A set of Braches enclose the body of a class.</p>

  
  
  
  
  
  
