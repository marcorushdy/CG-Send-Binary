# CG-Send-Binary
Convert your locally compiled binary to a C++ code/text format that you can use on Codingame.com

What it does:
* Converts the binary to base64 text encoding
* Outputs a .cpp file with code to recreate the binary file on the CG servers and run it

How to use:
* Compile this tool 
* Compile your AI as a linux binary
* Run this tool on the linux binary
* Use the "_Base64.cpp" file as your program on Codingame

I recommend you also:
* Strip the binary
* Compress it with [UPX](https://upx.github.io/)

before using this tool, to reduce the chance of hitting the 100ko code size limit of Codingame

Credits:
* Base64 code was copied from http://www.adp-gmbh.ch/cpp/common/base64.html
* Original idea is from [CPC]rOut on Codingame.com
