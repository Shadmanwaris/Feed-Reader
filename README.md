# Project Overview

 This project is a web-based application that reads RSS feeds. The original developer of this application clearly saw the value in testing, they've already included [Jasmine](http://jasmine.github.io/) and even started writing their first test suite! Unfortunately, they decided to move on to start their own company and we're now left with an application with an incomplete test suite. That's where you come in.


## Why this Project?

Testing is an important part of the development process and many organizations practice a standard of development known as "test-driven development". This is when developers write tests first, before they ever start developing their application. All the tests initially fail and then they start writing application code to make these tests pass.

Whether you work in an organization that uses test-driven development or in an organization that uses tests to make sure future feature development doesn't break existing features, it's an important skill to have!

## Setting up Local server :

1. First of all download ngrok.
2. Then to install (On Windows OS), open the .rar file and extract the files from it to a separate folder save ngrok.exe in it and to run double click the ngrok.exe file.
3. Then go to repo https://github.com/Shadmanwaris/Feed-Reader, clone or download the repository to your local computer to make change to your site for optimisation purpose.
4. Open the folder of your local repo, and copy the ngrok.exe file in it.
5. Now open bash from your current file location.And write following command to start the local server
	$> cd /path/to/your-project-folder
	$> python -m http.server 8080  or python -m SimpleHTTPServer 8080
6. Now double click to run ngrok.exe from local repo.
7. Type following command to be online from ngrok cmd.
	$> ./ngrok http 8080
8. Now open the browser and type 127.0.0.1:4040 localhost
9. It will provide you with two links, eg. https://d498d579.ngrok.io/ and other http://d498d579.ngrok.io/,please use https link because it is more secure and safe.
10. Through these link you can check the pagespeed by using your local server.
