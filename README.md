flipinstock
===========

Flipinstock lets you track a product's availability status on Flipkart. It can only be used on Linux based systems. Developed especially for the purpose, when the product is out of stock on Flipkart and there is a huge demand for it. If the product is out of stock, it informs users the moment product gets available.

Whenever the product gets available, it notifies users, by the method that they have chosen, and terminates when all the queried products have been reported to be in stock.

It can use the following applications to notify users, apart from system-notification and terminal:

	- Firefox
	- Mplayer
	- Google Chrome

For multiple products search, notification window won't show up until all the products have been reported to be in stock.
However, availibilty of each product will be notified individually by the system-notification, terminal and the apps chosen by the users.

###Requirements

Please ensure that you have zenity installed. Ubuntu & Fedora already have zenity & paplay preinstalled. 

If you are planning to use firefox, mplayer or chrome, please make sure that they are installed.

###Usage

+ Clone the repository
	```git clone https://github.com/sug4ndh/flipinstock.git```

+ Go inside the 'flipinstock' directory and execute the 'flipinstock-gui' file located inside the 'src' directory with 'bash'.

	E.g. If you have cloned it inside your home directory, this command can be used
	
	*```bash ~/flipinstock/src/flipinstock-gui```*

+ Fill up the info requested by the app, like the url of the product, select the apps to notify you and then sit back and enjoy. Flipinstock will notify you when your product gets available on Flipkart.

+ Alternatively, you can download the zip file from [here](https://github.com/sug4ndh/flipinstock/archive/master.zip). Extract it and then execute the 'flipinstock-gui' file inside the 'src' directory with bash.

	
+ E.g. If you have downloaded the zip file inside the ~/Downloads directory then run this command
	
	*```bash ~/Downloads/flipinstock/src/flipinstock-gui```* 
