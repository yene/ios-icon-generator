# iOS APP ICONS Generator

ios-icon-generator is a shell script which aim to generate iOS APP icons easier and simply.
![image](ios-icon-generator.gif)

### Check for alpha 
`identify -format '%[channels]' file` should not contain 'a'

### Usage
1. Install ImageMagick
	
	Before you run this script, please check whether you had install ImageMagick. If you don't have install. Follow this:
	<pre>
	brew install ImageMagick</pre>

2. Clone And Chmod
	<pre>
	git clone https://github.com/smallmuou/ios-icon-generator
	cd ios-icon-generator
	chmod 777 ios-icon-generator.sh
	</pre>
3. Run
	<pre>./ios-icon-generator.sh srcfile dstpath</pre>
