## Instructions  
Salam Walaikum,  
**bangla hadith rest api is to get Hadith in Bengali language. also it contains Hadiths in Arabic, and English**  


## Method  


**all request method is get.** 


*Credits: I don't know who created this hadiths digital database. i found some big sizes Hadiths database on internet. then, i organized and prepared it to use as api*  

*NOTE: i have tried my best to provide accurate information. but nobody is perfect. if you found any error please contact hello@nesaran.com. please test before use.*  


*jazakallah khair,*  
**Nesar Ahmed Naeem**  


| URL | Parameters | Details | Example | 
| :---         |     :---:      |          :--- |          :--- |
| https://bangla-hadith-api.herokuapp.com/hadithbook   | none     | get list of hadiths book available on my server    | https://bangla-hadith-api.herokuapp.com/hadithbook
| https://bangla-hadith-api.herokuapp.com/book/ "ID"   | ENTER BOOK ID.  eg. book/1 (here, 1=Sahih Bukhari (IFA)) id can be found here: https://bangla-hadith-api.herokuapp.com/hadithbook    | get list of hadith book data.    | https://bangla-hadith-api.herokuapp.com/book/1
| https://bangla-hadith-api.herokuapp.com/hadith/ "ID"   | ENTER SECTION ID.  eg. hadith/1 (here, 1=Revelation(ওহীর সূচনা) from book (Sahih Bukhari (IFA)))  Get book section from here: https://bangla-hadith-api.herokuapp.com/book/ "ID"  | get hadith by section id    | https://bangla-hadith-api.herokuapp.com/hadith/1
| https://bangla-hadith-api.herokuapp.com/hadith/status   | none | get hadith status code    | https://bangla-hadith-api.herokuapp.com/hadith/status
