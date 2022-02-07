# Ajax-contact-form

![alt text](https://webdesignerhut.com/wp-content/uploads/2014/07/Pass-Data-with-Ajax-to-a-PHP-file.png)

This is a Contact me Form Template in HTML5, CSS3, Bootstrap, Ajax, PHP.

Solution for localhost Xampp server not coonecting to mailserver issue

To configure XAMPP to send Mail from Localhost in PHP :

-go to the XAMPP installation directory and open the XAMPP folder 

-Go to the (C:xampp\php\php.ini) and open the PHP configuration setting file then find the [mail function] by scrolling down or simply press ctrl+f to search it directly then find the following lines and pass these values. Remember, there may be a semicolon ; at the starting of each line, simply remove the semicolon from each line which is given below.

/*code to be pasted in [mail function]*/

[𝐦𝐚𝐢𝐥 𝐟𝐮𝐧𝐜𝐭𝐢𝐨𝐧]

𝐅𝐨𝐫 𝐖𝐢𝐧𝟑𝟐 𝐨𝐧𝐥𝐲.

𝐡𝐭𝐭𝐩://𝐩𝐡𝐩.𝐧𝐞𝐭/𝐬𝐦𝐭𝐩

𝐒𝐌𝐓𝐏=𝐬𝐦𝐭𝐩.𝐠𝐦𝐚𝐢𝐥.𝐜𝐨𝐦

𝐡𝐭𝐭𝐩://𝐩𝐡𝐩.𝐧𝐞𝐭/𝐬𝐦𝐭𝐩-𝐩𝐨𝐫𝐭

𝐬𝐦𝐭𝐩_𝐩𝐨𝐫𝐭=𝟓𝟖𝟕

𝐬𝐞𝐧𝐝𝐦𝐚𝐢𝐥_𝐟𝐫𝐨𝐦 = 𝐲𝐨𝐮𝐫_𝐞𝐦𝐚𝐢𝐥_𝐚𝐝𝐝𝐫𝐞𝐬𝐬_𝐡𝐞𝐫𝐞

𝐬𝐞𝐧𝐝𝐦𝐚𝐢𝐥_𝐩𝐚𝐭𝐡 = "\"𝐂:\𝐱𝐚𝐦𝐩𝐩\𝐬𝐞𝐧𝐝𝐦𝐚𝐢𝐥\𝐬𝐞𝐧𝐝𝐦𝐚𝐢𝐥.𝐞𝐱𝐞\" -𝐭"


press ctrl+s to save this file and then close it.

-Now, go the (C:\xampp\sendmail\sendmail.ini) and open the sendmail configuration setting file then find sendmail by scrolling down or press ctrl+f to search it directly then find the following lines and pass these values. Remember, there may be a semicolon ; at the starting of each line, simply remove the semicolon from each line which is given below.

/*code to be pasted in sendmail*/

𝐬𝐦𝐭𝐩_𝐬𝐞𝐫𝐯𝐞𝐫=𝐬𝐦𝐭𝐩.𝐠𝐦𝐚𝐢𝐥.𝐜𝐨𝐦

𝐬𝐦𝐭𝐩_𝐩𝐨𝐫𝐭=𝟓𝟖𝟕

𝐞𝐫𝐫𝐨𝐫_𝐥𝐨𝐠𝐟𝐢𝐥𝐞=𝐞𝐫𝐫𝐨𝐫.𝐥𝐨𝐠

𝐝𝐞𝐛𝐮𝐠_𝐥𝐨𝐠𝐟𝐢𝐥𝐞=𝐝𝐞𝐛𝐮𝐠.𝐥𝐨𝐠

𝐚𝐮𝐭𝐡_𝐮𝐬𝐞𝐫𝐧𝐚𝐦𝐞= /*𝐞𝐦𝐚𝐢𝐥 𝐡𝐞𝐫𝐞*/

𝐚𝐮𝐭𝐡_𝐩𝐚𝐬𝐬𝐰𝐨𝐫𝐝= /*𝐞𝐦𝐚𝐢𝐥 𝐩𝐚𝐬𝐬𝐰𝐨𝐫𝐝*/

𝐟𝐨𝐫𝐜𝐞_𝐬𝐞𝐧𝐝𝐞𝐫= /*𝐞𝐦𝐚𝐢𝐥 𝐡𝐞𝐫𝐞*/ (𝐢𝐭'𝐬 𝐨𝐩𝐭𝐢𝐨𝐧𝐚𝐥)


press ctrl+s to save this file and then close it.

-After all changes in the two files, don’t forget to restart your apache server.

𝐍𝐨𝐭𝐞: 𝐈𝐟 𝐲𝐨𝐮𝐫 𝐦𝐚𝐢𝐥 𝐢𝐬𝐧’𝐭 𝐬𝐞𝐧𝐭 𝐚𝐟𝐭𝐞𝐫 𝐭𝐡𝐞 𝐜𝐨𝐫𝐫𝐞𝐜𝐭 𝐜𝐡𝐚𝐧𝐠𝐞𝐬 𝐚𝐧𝐝 𝐲𝐨𝐮 𝐠𝐨𝐭 𝐚 𝐰𝐚𝐫𝐧𝐢𝐧𝐠 𝐨𝐫 𝐞𝐫𝐫𝐨𝐫. 
𝐏𝐥𝐞𝐚𝐬𝐞 𝐜𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐞 𝐲𝐨𝐮𝐫 𝐠𝐨𝐨𝐠𝐥𝐞 𝐚𝐜𝐜𝐨𝐮𝐧𝐭 𝐬𝐞𝐜𝐮𝐫𝐢𝐭𝐲 𝐚𝐬 “𝐋𝐞𝐬𝐬 𝐬𝐞𝐜𝐮𝐫𝐞 𝐚𝐩𝐩𝐬”. 
𝐓𝐨 𝐜𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐞 𝐢𝐭: – 𝐆𝐨 𝐭𝐨 𝐲𝐨𝐮𝐫 𝐆𝐨𝐨𝐠𝐥𝐞 𝐚𝐜𝐜𝐨𝐮𝐧𝐭 𝐭𝐡𝐞𝐧 𝐜𝐥𝐢𝐜𝐤 𝐨𝐧 𝐭𝐡𝐞 𝐒𝐞𝐜𝐮𝐫𝐢𝐭𝐲 𝐭𝐚𝐛 𝐚𝐧𝐝 𝐬𝐜𝐫𝐨𝐥𝐥 𝐝𝐨𝐰𝐧, 𝐭𝐡𝐞𝐫𝐞 𝐲𝐨𝐮 𝐜𝐚𝐧 𝐬𝐞𝐞 𝐭𝐡𝐞 𝐋𝐞𝐬𝐬 𝐬𝐞𝐜𝐮𝐫𝐞 𝐚𝐩𝐩 𝐚𝐜𝐜𝐞𝐬𝐬 𝐩𝐚𝐧𝐞𝐥, 𝐒𝐢𝐦𝐩𝐥𝐲 𝐭𝐮𝐫𝐧 𝐨𝐧 𝐭𝐡𝐚𝐭. 
𝐓𝐡𝐢𝐬 𝐩𝐚𝐧𝐞𝐥 𝐨𝐧𝐥𝐲 𝐬𝐡𝐨𝐰𝐬 𝐢𝐟 𝐲𝐨𝐮 𝐡𝐚𝐯𝐞𝐧’𝐭 𝐞𝐧𝐚𝐛𝐥𝐞𝐝 𝟐-𝐒𝐭𝐞𝐩 𝐕𝐞𝐫𝐢𝐟𝐢𝐜𝐚𝐭𝐢𝐨𝐧.

𝐓𝐡𝐢𝐬 𝐢𝐬 𝐟𝐨𝐫 𝐭𝐞𝐬𝐭𝐢𝐧𝐠 𝐩𝐮𝐫𝐩𝐨𝐬𝐞𝐬.
𝐏𝐥𝐞𝐚𝐬𝐞 𝐜𝐨𝐧𝐟𝐢𝐠𝐮𝐫𝐞 𝐲𝐨𝐮𝐫 𝐠𝐨𝐨𝐠𝐥𝐞 𝐚𝐜𝐜𝐨𝐮𝐧𝐭 𝐬𝐞𝐜𝐮𝐫𝐢𝐭𝐲 𝐚𝐬 “𝐋𝐞𝐬𝐬 𝐬𝐞𝐜𝐮𝐫𝐞 𝐚𝐩𝐩𝐬” 𝐭𝐨 𝐎𝐅𝐅 𝐨𝐧𝐜𝐞 𝐲𝐨𝐮 𝐚𝐫𝐞 𝐝𝐨𝐧𝐞 𝐭𝐞𝐬𝐭𝐢𝐧𝐠 𝐚𝐬 𝐆𝐨𝐨𝐠𝐥𝐞 𝐫𝐞𝐜𝐨𝐦𝐦𝐞𝐧𝐝𝐬 𝐢𝐭 𝐨𝐟𝐟 𝐟𝐨𝐫 𝐬𝐞𝐜𝐮𝐫𝐢𝐭𝐲 𝐩𝐮𝐫𝐩𝐨𝐬𝐞𝐬 𝐨𝐟 𝐆𝐨𝐨𝐠𝐥𝐞 𝐀𝐜𝐜𝐨𝐮𝐧𝐭.
