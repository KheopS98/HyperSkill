# JetBrains Academy HyperSkill Java Developer
<p>Link: <link>https://hyperskill.org/curriculum</link></p>

## I. Introduction to Java

<p><code>Key Feture:</code> Platform independence "Write once, Run anywhere"</p>
<p><code>Used:</code> Android, Finacial Service Industry, Telecomunication, Embedded Systems, Medical Applications.</p>
<p><code>Java has:</code> Garbage Collector-> Automatic cleans the memory from unused ubjects during runtime.</p>
<p><code>Primary</code> an imperativ language based on OOP concepts: almost every part of the program is an object. U can say it's a full interaction between objects.</p>
<p><code>Support Modern Programming Paradigms:</code></p>
<ul>
  <li>Generic Programming</li>
  <li>Concurrent Programming</li>
  <li>Functional Programming</li>
</ul>


## II. Literals
<p>Values of different datatypes are called <code>literals</code>.</p>
<p><code>Integer Literals</codcode></p>

<p>0, 1, 3, 10, 1000, 1500</p>
<p>For more readability we an use ' _ ' symbol. <code>Example:</code> 1000235745 -> 1_000_235_745</p>
<hr>
<p><code>Character Literals</code></p>
<p>A single character represent a letter , a number, a symbol using a <code>Single Quote</code> 'A', 'C', '7', '!', '$', " ", '_'.</p>
<p>Don't confuse <b>7</b> with <b>'7'</b> those are not the same.</p>
<p>A Character can't include 2 or more digits, letters, symbols because it represent only one Character.</p>
<p><code>Incorrect Character Liteals:</code> '123', 'abc'</p>
<hr>
<p><code>String Literls</code></p>
<p>Sequence of Characters. They represent text information.</p>
<p>To Write a String we use <b>Double Quotes</b> " "</p>
<p>"Text I want to learn Java."</p>
<hr>
<p><code>!!Remeber!!</code></p>
<p>Do not confuse literals.</p>
<p>123 is Integer || "123" is String</p>
<p>'A' is Char || "A" is String</p>
<p>'1' is Char || 1 is Integer</p>
<hr>
  
## III. Overview of the basic program
<p><code>Hello World</code></p>
<pre><code>
class Main{
    public static void main(String [] args){
        System.out.println("Hello, Tony!");
    }
} </code></pre>

<p><code>Basic Terminology:</b></p>
<p><code>Program:</code> a sequence of instructions called "Statements" executed one by one, in order from top to bot.</p>
<p><code>Statement:</code> a single action terminated by a ;</p>
<p><code>Block:</code> a group of 0 or more statements enclosed by {...}.</p>
<p><code>Method:</code> a sequence of staments that represent a high-level operation(known as subprogram or procedure).</p>
<p><code>Syntax:</code> a set of rules that define how the program should be writed.</p>
<p><code>Keywords:</code> a word that have a specific meaning in the programming language(public, class). Can't be used as names for variables or functions.</p>
<p><code>Identifier:</code> a word that refer to something in the program(such as variable name or function name).</p>
<p><code>Comment:</code> a textual explanation of what code does. Comments are ignored at runtine. Comments start with // single-line</p>
<p><code>WhiteSpace:</code> all characters that are not visible(space, tab, newline).</p>
<hr>

## III.1 The HelloWorld Program under the Microscope
<pre><code>
class Main{
    public static void main(String [] args){
        System.out.println("Hello, Tony!");
    }
} </code></pre>
<p><code>1. public class</code></p>
<p>It's the basic unit of program. Every Java program must have at least one class.</p>
<p>A <b>class</b> can have any name <code>'App'</code>, <code>'Main'</code>, <code>'Program'</code> but it must not start with  a digit.</p>
<p>A set of <code>Braches {...}</code> enclose the body of a class.</p>

  
  
  
  
  
  
