Getting started for "Scala" using Git in WIndows
<br>
Download <a href="http://downloads.typesafe.com/scala/2.11.6/scala-2.11.6.msi?_ga=1.43445996.83007189.1427963521">Scala</a><br>
<br>
Using Git, <br>
<code>$cd "/d/scala/bin"</code><br>
<br>
For testing:- Write a very basic file <br>
```scala
object helloworld {
	def main(args:Array[String]) {
		println("Hello Meow!")
	}
}
```
save it as <code>helloworld.scala</code> in <code>bin folder</code><br>
The object name should be same as the file name. This language is kinda mix of java, c and python. <br>
<br>
<code>$scalac helloworld.scala</code><br>
<code>$scala -classpath . helloworld</code><br>
<br>
Ok done.
<br><br>
Why this repo? <br>
In this repo, i will be adding some basics of scala gained through self-learning.
<br>
