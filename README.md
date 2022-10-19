Salam Walaikum,  
**bangla hadith api collection. also it contains Hadiths in Arabic, Bangla and English**  
**all request method is get.**  
*NOTE: i have tried my best to provide accurate information. but nobody perfects. i could be wrong because i am human too. if you found any error please contact hello@nesaran.com. please test before use.*  
*jazakallah khair,*  
**Nesar Ahmed Naeem**  
*Junior Full-stack Developer*

| URL | Parameters | Details | Example | 
| :---         |     :---:      |          :--- |          :--- |
| https://bangla-hadith-api.herokuapp.com/hadithbook   | none     | get list of hadith book available on my server    | https://bangla-hadith-api.herokuapp.com/hadithbook
| https://bangla-hadith-api.herokuapp.com/book/ "ID"   | ENTER BOOK ID.  eg. book/1 (here, 1=Sahih Bukhari (IFA)) id can be found here: https://bangla-hadith-api.herokuapp.com/hadithbook    | get list of hadith book available on my server    | https://bangla-hadith-api.herokuapp.com/book/1
| https://bangla-hadith-api.herokuapp.com/hadith/ "ID"   | ENTER SECTION ID.  eg. hadith/1 (here, 1=Revelation(ওহীর সূচনা) from book (Sahih Bukhari (IFA)))  Get book section from here: https://bangla-hadith-api.herokuapp.com/book/ "ID"  | get hadith by section id    | https://bangla-hadith-api.herokuapp.com/hadith/1
| https://bangla-hadith-api.herokuapp.com/hadith/status   | none | get hadith status code    | https://bangla-hadith-api.herokuapp.com/hadith/status
