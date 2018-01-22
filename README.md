# imgdrive_translations
Traslations of ImgDrive: http://www.yubsoft.com/imgdrive/

ImgDrive use binary format file of language file like IMGDRIVE_XXX.lng, which is generated by IMGDRIVE_XXX.ini file.

# Transalte Step
1. Search LCID from LCID table below, create new file named IMGDRIVE_[LCID].ini with content of IMGDRIVE_ENG.ini
2. Translate  
[INFO]
Language=**English**    => Will be show in Settings dialog  
LanguageID=$**0409**    => !important, must be changed to the value list in LCID section  
Version=**1.0.1.0**  
Author=**Yubsoft**  
[DIALOG_1]  
0=**General**  
3=**&Language:**  
...

3. Double click ini2lng to translate IMGDRIVE_XXX.ini to IMGDRIVE_XXX.lng
4. Copy the IMGDRIVE_XXX.lng to c:\Program Files\ImgDrive\Language\  
If all goes well, the new translated language will be listed in ImgDrive's settings dialog.

# LCID
<table border="0" cellpadding=5 cols=13 frame=below rules=rows>
  <tr> 
    <th align=left>Primary Language</th>
    <th align=left>Locale Name</th>
    <th align=left>LCID</th>
  </tr>
  <tr> 
    <td>Afrikaans</td>
    <td>Afrikaans</td>
    <td>(0436; AFK)</td>
  </tr>
  <tr> 
    <td>Albanian</td>
    <td>Albanian</td>
    <td>(041c; SQI)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Saudi Arabia)</td>
    <td>(0401; ARA)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Iraq)</td>
    <td>(0801; ARI)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Egypt)</td>
    <td>(0C01; ARE)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Libya)</td>
    <td>(1001; ARL)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Algeria)</td>
    <td>(1401; ARG)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Morocco)</td>
    <td>(1801; ARM)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Tunisia)</td>
    <td>(1C01; ART)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Oman)</td>
    <td>(2001; ARO)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Yemen)</td>
    <td>(2401; ARY)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Syria)</td>
    <td>(2801; ARS)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Jordan)</td>
    <td>(2C01; ARJ)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Lebanon)</td>
    <td>(3001; ARB)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Kuwait)</td>
    <td>(3401; ARK)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (U.A.E.)</td>
    <td>(3801; ARU)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Bahrain)</td>
    <td>(3C01; ARH)</td>
  </tr>
  <tr> 
    <td>Arabic</td>
    <td>Arabic (Qatar)</td>
    <td>(4001; ARQ)</td>
  </tr>
  <tr> 
    <td>Armenian</td>
    <td>Armenian</td>
    <td>(042b; HYE)</td>
  </tr>
  <tr> 
    <td>Assamese</td>
    <td>Assamese</td>
    <td>(044d; ASM)</td>
  </tr>
  <tr> 
    <td>Azeri</td>
    <td>Azeri (Latin)</td>
    <td>(042c; AZE)</td>
  </tr>
  <tr> 
    <td>Azeri</td>
    <td>Azeri (Cyrillic)</td>
    <td>(082c; AZC)</td>
  </tr>
  <tr> 
    <td>Basque</td>
    <td>Basque</td>
    <td>(042D; EUQ)</td>
  </tr>
  <tr> 
    <td>Belarussian</td>
    <td>Belarussian</td>
    <td>(0423, BEL)</td>
  </tr>
  <tr> 
    <td>Bengali</td>
    <td>Bengali</td>
    <td>(0445; BEN)</td>
  </tr>
  <tr> 
    <td>Bulgarian</td>
    <td>Bulgarian</td>
    <td>(0402, BGR)</td>
  </tr>
  <tr> 
    <td>Catalan</td>
    <td>Catalan</td>
    <td>(0403; CAT)</td>
  </tr>
  <tr> 
    <td>Chinese</td>
    <td>Chinese (Taiwan)</td>
    <td>(0404; CHT)</td>
  </tr>
  <tr> 
    <td>Chinese</td>
    <td>Chinese (PRC)</td>
    <td>(0804; CHS)</td>
  </tr>
  <tr> 
    <td>Chinese</td>
    <td>Chinese (Hong Kong SAR)</td>
    <td>(0C04; ZHH)</td>
  </tr>
  <tr> 
    <td>Chinese</td>
    <td>Chinese (Singapore)</td>
    <td>(1004; ZHI)</td>
  </tr>
  <tr> 
    <td>Chinese</td>
    <td>Chinese (Macau SAR)</td>
    <td>(1404; ZHM)</td>
  </tr>
  <tr> 
    <td>Croatian</td>
    <td>Croatian</td>
    <td>(041a; HRV)</td>
  </tr>
  <tr> 
    <td>Czech</td>
    <td>Czech</td>
    <td>(0405; CSY)</td>
  </tr>
  <tr> 
    <td>Danish</td>
    <td>Danish</td>
    <td>(0406; DAN)</td>
  </tr>
  <tr> 
    <td>Dutch</td>
    <td>Dutch (Netherlands)</td>
    <td>(0413; NLD)</td>
  </tr>
  <tr> 
    <td>Dutch</td>
    <td>Dutch (Belgium)</td>
    <td>(0813; NLB)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (United States)</td>
    <td>(0409; ENU)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (United Kingdom)</td>
    <td>(0809; ENG)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (Australia)</td>
    <td>(0c09; ENA)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (Canada)</td>
    <td>(1009; ENC)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (New Zealand)</td>
    <td>(1409; ENZ)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (Ireland)</td>
    <td>(1809; ENI)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (South Africa)</td>
    <td>(1c09; ENS)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (Jamaica)</td>
    <td>(2009; ENJ)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (Caribbean)</td>
    <td>(2409; ENB)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (Belize)</td>
    <td>(2809; ENL)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (Trinidad)</td>
    <td>(2c09; ENT)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (Zimbabwe)</td>
    <td>(3009; ENW)</td>
  </tr>
  <tr> 
    <td>English</td>
    <td>English (Philippines)</td>
    <td>(3409; ENP)</td>
  </tr>
  <tr> 
    <td>Estonian</td>
    <td>Estonian</td>
    <td>(0425, ETI)</td>
  </tr>
  <tr> 
    <td>Faeroese</td>
    <td>Faeroese</td>
    <td>(0438, FOS)</td>
  </tr>
  <tr> 
    <td>Farsi</td>
    <td>Farsi</td>
    <td>(0429; FAR)</td>
  </tr>
  <tr> 
    <td>Finnish</td>
    <td>Finnish</td>
    <td>(040b; FIN)</td>
  </tr>
  <tr> 
    <td>French</td>
    <td>French (France)</td>
    <td>(040c; FRA)</td>
  </tr>
  <tr> 
    <td>French</td>
    <td>French (Belgium)</td>
    <td>(080c; FRB)</td>
  </tr>
  <tr> 
    <td>French</td>
    <td>French (Canada)</td>
    <td>(0c0c; FRC)</td>
  </tr>
  <tr> 
    <td>French</td>
    <td>French (Switzerland)</td>
    <td>(100c; FRS)</td>
  </tr>
  <tr> 
    <td>French</td>
    <td>French (Luxembourg)</td>
    <td>(140c; FRL)</td>
  </tr>
  <tr> 
    <td>French</td>
    <td>French (Monaco)</td>
    <td>(180c; FRM)</td>
  </tr>
  <tr> 
    <td>Georgian</td>
    <td>Georgian</td>
    <td>(0437; KAT)</td>
  </tr>
  <tr> 
    <td>German</td>
    <td>German (Germany)</td>
    <td>(0407; DEU)</td>
  </tr>
  <tr> 
    <td>German</td>
    <td>German (Switzerland)</td>
    <td>(0807; DES)</td>
  </tr>
  <tr> 
    <td>German</td>
    <td>German (Austria)</td>
    <td>(0c07; DEA)</td>
  </tr>
  <tr> 
    <td>German</td>
    <td>German (Luxembourg)</td>
    <td>(1007; DEL)</td>
  </tr>
  <tr> 
    <td>German</td>
    <td>German (Liechtenstein)</td>
    <td>(1407; DEC)</td>
  </tr>
  <tr> 
    <td>Greek</td>
    <td>Greek</td>
    <td>(0408; ELL)</td>
  </tr>
  <tr> 
    <td>Gujarati</td>
    <td>Gujarati</td>
    <td>(0447; GUJ)</td>
  </tr>
  <tr> 
    <td>Hebrew</td>
    <td>Hebrew</td>
    <td>(040D; HEB)</td>
  </tr>
  <tr> 
    <td>Hindi</td>
    <td>Hindi</td>
    <td>(0439; HIN)</td>
  </tr>
  <tr> 
    <td>Hungarian</td>
    <td>Hungarian</td>
    <td>(040e; HUN)</td>
  </tr>
  <tr> 
    <td>Icelandic</td>
    <td>Icelandic</td>
    <td>(040F; ISL)</td>
  </tr>
  <tr> 
    <td>Indonesian</td>
    <td>Indonesian</td>
    <td>(0421; IND)</td>
  </tr>
  <tr> 
    <td>Italian</td>
    <td>Italian (Italy)</td>
    <td>(0410; ITA)</td>
  </tr>
  <tr> 
    <td>Italian Italian</td>
    <td>(Switzerland)</td>
    <td>(0810; ITS)</td>
  </tr>
  <tr> 
    <td>Japanese</td>
    <td>Japanese</td>
    <td>(0411; JPN)</td>
  </tr>
  <tr> 
    <td>Kannada</td>
    <td>Kannada</td>
    <td>(044b; KAN)</td>
  </tr>
  <tr> 
    <td>Kashmiri</td>
    <td>Kashmiri (India)</td>
    <td>(0860; KAI)</td>
  </tr>
  <tr> 
    <td>Kazakh</td>
    <td>Kazakh</td>
    <td>(043f; KAZ)</td>
  </tr>
  <tr> 
    <td>Konkani</td>
    <td>Konkani</td>
    <td>(0457; KOK)</td>
  </tr>
  <tr> 
    <td>Korean</td>
    <td>Korean</td>
    <td>(0412; KOR)</td>
  </tr>
  <tr> 
    <td>Korean</td>
    <td>Korean (Johab)</td>
    <td>(0812; KOJ)</td>
  </tr>
  <tr> 
    <td>Latvian</td>
    <td>Latvian</td>
    <td>(0426, LVI)</td>
  </tr>
  <tr> 
    <td>Lithuanian</td>
    <td>Lithuanian</td>
    <td>(0427, LTH)</td>
  </tr>
  <tr> 
    <td>Lithuanian</td>
    <td>Lithuanian (Classic)</td>
    <td>(0827, LTH)</td>
  </tr>
  <tr> 
    <td>FYOR Macedonian</td>
    <td>FYOR Macedonian</td>
    <td>(042f; MKD)</td>
  </tr>
  <tr> 
    <td>Malay</td>
    <td>Malaysian</td>
    <td>(043e;MSL)</td>
  </tr>
  <tr> 
    <td>Malay</td>
    <td>Malay Brunei Darussalam</td>
    <td>(083e;MSB)</td>
  </tr>
  <tr> 
    <td>Malayalam</td>
    <td>Malayalam</td>
    <td>(044c; MAL)</td>
  </tr>
  <tr> 
    <td>Marathi</td>
    <td>Marathi</td>
    <td>(044e; MAR)</td>
  </tr>
  <tr> 
    <td>Nepali</td>
    <td>Nepali (Nepal)</td>
    <td>(0461; NEP)</td>
  </tr>
  <tr> 
    <td>Nepali</td>
    <td>Nepali (India)</td>
    <td>(0861; NEI)</td>
  </tr>
  <tr> 
    <td>Norwegian</td>
    <td>Norwegian (Bokmal)</td>
    <td>(0414; NOR)</td>
  </tr>
  <tr> 
    <td>Norwegian</td>
    <td>Norwegian (Nynorsk)</td>
    <td>(0814; NON)</td>
  </tr>
  <tr> 
    <td>Oriya</td>
    <td>Oriya</td>
    <td>(0448; ORI)</td>
  </tr>
  <tr> 
    <td>Polish</td>
    <td>Polish</td>
    <td>(0415; PLK)</td>
  </tr>
  <tr> 
    <td>Portuguese</td>
    <td>Portuguese (Brazil)</td>
    <td>(0416; PTB)</td>
  </tr>
  <tr> 
    <td>Portuguese</td>
    <td>Portuguese (Portugal)</td>
    <td>(0816; PTG)</td>
  </tr>
  <tr> 
    <td>Punjabi</td>
    <td>Punjabi</td>
    <td>(0446; PAN)</td>
  </tr>
  <tr> 
    <td>Rhaeto-Romanic</td>
    <td>Rhaeto-Romanic</td>
    <td>(0417; RMS)</td>
  </tr>
  <tr> 
    <td>Romanian</td>
    <td>Romanian</td>
    <td>(0418, ROM)</td>
  </tr>
  <tr> 
    <td>Romanian</td>
    <td>Romanian (Moldova)</td>
    <td>(0818, ROV)</td>
  </tr>
  <tr> 
    <td>Russian</td>
    <td>Russian</td>
    <td>(0419; RUS)</td>
  </tr>
  <tr> 
    <td>Russian</td>
    <td>Russian (Moldova)</td>
    <td>(0819, RUM)</td>
  </tr>
  <tr> 
    <td>Sami</td>
    <td>Sami (Lappish)</td>
    <td>(043b; SZI)</td>
  </tr>
  <tr> 
    <td>Sanskrit</td>
    <td>Sanskrit</td>
    <td>(044f; SAN)</td>
  </tr>
  <tr> 
    <td>Serbian</td>
    <td>Serbian (Cyrillic)</td>
    <td>(0c1a; SRB)</td>
  </tr>
  <tr> 
    <td>Serbian</td>
    <td>Serbian (Latin)</td>
    <td>(081a; SRL)</td>
  </tr>
  <tr> 
    <td>Sindhi</td>
    <td>Sindhi</td>
    <td>(0459; SND)</td>
  </tr>
  <tr> 
    <td>Slovak</td>
    <td>Slovak</td>
    <td>(041b; SKY)</td>
  </tr>
  <tr> 
    <td>Slovenian</td>
    <td>Slovenian</td>
    <td>(0424, SLV)</td>
  </tr>
  <tr> 
    <td>Sorbian</td>
    <td>Sorbian</td>
    <td>(042e, SBN)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Spain - Traditional Sort)</td>
    <td>(040a; ESP)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Mexico)</td>
    <td>(080a; ESM)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Spain - Modern Sort)</td>
    <td>(0c0a; ESN)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Guatemala)</td>
    <td>(100a; ESG)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Costa Rica)</td>
    <td>(140a; ESC)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Panama)</td>
    <td>(180a; ESA)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Dominican Republic)</td>
    <td>(1c0a; ESD)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Venezuela)</td>
    <td>(200a; ESV)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Colombia)</td>
    <td>(240a; ESO)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Peru)</td>
    <td>(280a; ESR)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Argentina)</td>
    <td>(2c0a; ESS)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Ecuador)</td>
    <td>(300a; ESF)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Chile)</td>
    <td>(340a; ESL)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Uruguay)</td>
    <td>(380a; ESY)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Paraguay)</td>
    <td>(3c0a; ESZ)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Bolivia)</td>
    <td>(400a; ESB)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (El Salvador)</td>
    <td>(440a; ESE)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Honduras)</td>
    <td>(480a; ESH)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Nicaragua)</td>
    <td>(4c0a; ESI)</td>
  </tr>
  <tr> 
    <td>Spanish</td>
    <td>Spanish (Puerto Rico)</td>
    <td>(500a; ESU</td>
  </tr>
  <tr> 
    <td>Sutu</td>
    <td>Sutu</td>
    <td>(0430; SXT)</td>
  </tr>
  <tr> 
    <td>Swahili</td>
    <td>Swahili (Kenya)</td>
    <td>(0441; SWK)</td>
  </tr>
  <tr> 
    <td>Swedish</td>
    <td>Swedish</td>
    <td>(041D; SVE)</td>
  </tr>
  <tr> 
    <td>Swedish</td>
    <td>Swedish (Finland)</td>
    <td>(081d; SVF)</td>
  </tr>
  <tr> 
    <td>Tamil</td>
    <td>Tamil</td>
    <td>(0449; TAM)</td>
  </tr>
  <tr> 
    <td>Tatar</td>
    <td>Tatar (Tatarstan)</td>
    <td>(0444; TAT)</td>
  </tr>
  <tr> 
    <td>Telugu</td>
    <td>Telugu</td>
    <td>(044a; TEL)</td>
  </tr>
  <tr> 
    <td>Thai</td>
    <td>Thai</td>
    <td>(041E; THA)</td>
  </tr>
  <tr> 
    <td>Tsonga</td>
    <td>Tsonga</td>
    <td>(0431; TSG)</td>
  </tr>
  <tr> 
    <td>Tswana</td>
    <td>Tswana</td>
    <td>(0432; TNA)</td>
  </tr>
  <tr> 
    <td>Turkish</td>
    <td>Turkish</td>
    <td>(041f; TRK)</td>
  </tr>
  <tr> 
    <td>Ukrainian</td>
    <td>Ukrainian</td>
    <td>(0422, UKR)</td>
  </tr>
  <tr> 
    <td>Urdu</td>
    <td>Urdu (Pakistan)</td>
    <td>(0420; URD)</td>
  </tr>
  <tr> 
    <td>Urdu</td>
    <td>Urdu (India)</td>
    <td>(0820; URI)</td>
  </tr>
  <tr> 
    <td>Uzbek</td>
    <td>Uzbek (Latin)</td>
    <td>(0443; UZB)</td>
  </tr>
  <tr> 
    <td>Uzbek</td>
    <td>Uzbek (Cyrillic)</td>
    <td>(0843; UZC)</td>
  </tr>
  <tr> 
    <td>Venda</td>
    <td>Venda</td>
    <td>(0433; VEN)</td>
  </tr>
  <tr> 
    <td>Vietnamese</td>
    <td>Vietnamese</td>
    <td>(042a; VIT)</td>
  </tr>
  <tr> 
    <td>Xhosa</td>
    <td>Xhosa</td>
    <td>(0434; XHS)</td>
  </tr>
  <tr> 
    <td>Yiddish</td>
    <td>Yiddish</td>
    <td>(043d; JII)</td>
  </tr>
  <tr> 
    <td>Zulu</td>
    <td>Zulu</td>
    <td>(0435; ZUL)</td>
  </tr>
</table>
