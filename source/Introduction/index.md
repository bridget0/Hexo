title: Introduction

---

Red is a new programming language, strongly inspired by REBOL, but with a broader field of usage thanks to its native-code compiler, from system programming to high-level scripting, while providing modern support for concurrency and multi-core CPUs.

### Main characteristics are:
<ul>
	<li>Functional, imperative and symbolic</li>
	<li>Prototype-based object support</li>
	<li>Homoiconic (Red is its own meta-language)</li>
	<li>Optionally typed, rich set of datatypes (50+)</li>
	<li>Both statically and JIT-compiled to native code</li>
	<li>Concurrency and parallelism strong support (actors, parallel collections)</li>
	<li>Low-level system programming abilities through the built-in Red/System DSL</li>
	<li>High-level scripting and REPL console support</li>
	<li>Highly embeddable</li>
	<li>Low memory footprint, garbage collected</li>
	<li>Low disk footprint (< 1MB)</li>
</ul>

### Making a Red "Hello World"
The Red toolchain comes as a single half-megabyte executable file that you can download from here for the big-3 platforms. 
<p>
<ol>
	<li>Put the downloaded red binary in a folder that's in the PATH, or just in the working folder.</li>
	<li>In a code or text editor, write the following Hello World program:
	``` bash
	Red [
	    Title: "Simple hello world script"
	]
	
	print "Hello World!"
	```
	</li>
	<li>Save it under the name: hello.red</li>
	<li>From a terminal (works from DOS too), run it with:
	``` bash
	$ red hello.red
	```
	</li>
	<li>You should see the Hello World! output.</li>
	<li>Want to generate a compiled executable from that program?
	``` bash
	$ red -c hello.red
	$ ./hello
	```
	</li>
	<li>Want to cross-compile to another supported platform?
	``` bash
	$ red -t Windows hello.red
	$ red -t Darwin hello.red
	$ red -t Linux-ARM hello.red
	```
	</li>
</ol>
</p>


