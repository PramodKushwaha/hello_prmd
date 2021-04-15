This is my first package "hello_prmd"

# Installation
	composer require prmd/hello_prmd
# Usage
if you want to print then follow below steps 
- Create index.php file on root directory
- In index.php file first include autoload.php file from vendor folder
- Create object for "HelloPrmd" class
- Call method "printHello()"
# Example index.php 
	<?php 
		require_once './vendor/autoload.php';
		
		$print = new \HelloPrmd\HelloPrmd();
		print_r($print->printHello());
