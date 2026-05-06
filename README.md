<div align="center">
  <img src="https://raw.githubusercontent.com/nikzad-avasam/downloader/refs/heads/main/dl-icon.gif" width="400" alt="wide-2" />
</div>


🎬 برای دانلود ویدیوهای یوتیوب از این پروژه استفاده کنید :‌
https://github.com/nikzad-avasam/youtube-dl


 


## ⬇️ دانلود کننده فایل + 🌐 مرورگر وب 

- ✅  دانلود کننده هر فایلی از هرکجا درون گیتهاب شما  
- ✅  پشتیبانی از فایل های بزرگ چند گیگابایتی
- 🔐 امکان رمزگذاری روی فایل های دانلود شده جهت محافظت
- ✅  استفاده از پکیج aria2 جهت دانلود بدون مشکل 
- ✅  دانلود هر نوع فایلی و فشرده سازی اتوماتیک و تحویل بصورت زیپ شده و پارت بندی شده ( هر پارت ۹۰ مگابایت )
- ✅ انجام تمام کارها بصورت خودکار و بدون نیاز به تنظیمات خاص
- ✅ پشتیبانی از دانلود همزمان چندین لینک
- ✅ امکان دسته بندی فایل های zip درون پوشه های هم نام با فایل
- ✅ امکان حذف یکجای تمام فایلهای دانلود شده 
- ✅ ذخیره سازی دائمی فایل ها در گیتهاب خودتان
- حتما بخش بروزرسانی ها را در پایین صفحه بخوانید.
- لطفا توجه کنید که برخی سرورهای ایرانی ای پی های خارج را مسدود کرده است مثلا سافت ۹۸ و امکان دانلود فایلهای آنها با استفاده از این ابزار نیست.
- 🌐 مرورگر وب اضافه شد به قسمت بروزرسانی مراجعه کنید و نحوه ی استفاده را مطلع شوید.
- 📹 آموزش ویدیویی استفاده از این ابزار به انتهای همین مطلب اضافه شد.
a
---

## 🔧 آموزش نصب

- درون این ریپازیتوری و در قسمت بالا روی دکمه ی fork بزنید.
- سپس در صورت نیاز میتوانید نام فورک را عوض کنید و در نهایت روی دکمه ی Create Fork بزنید.
- ریپازیتوری شما آماده است و اکنون میتوانید هر فایلی را که لینک دانلود آنرا دارید درون ریپازیتوری خود دانلود کنید و سپس از درون ریپازیتوری به سیستم خودتان دانلود کنید.

---

## 🎯 نحوه ی دانلود کردن فایل درون ریپازیتوری

- ۱- لینک خود را بصورت مستقیم مثل example.com/files/something.zip آماده کنید.
- ۲- به گیتهاب خود رفته و روی ریپازیتوری فورک شده بزنید و قسمت Actions را انتخاب کنید.
- ۳- در قسمت Actions شما لیست workflow ها را میبینید که یک عدد workflow داریم به اسم AVASAM - Download from URLs & Save to Repo  . روی آن بزنید و بعد از باز شدن روی Run Workflow بزنید آدرس دانلود از شما خواسته میشود و سپس شروع به دانلود .....

---


## 📂 فایلها را از کجا دانلود کنیم

همه فایلهای دانلود شده در پوشه ی downloads درون ریپازیتوری شما اضافه میشوند.فایل ها بصورت تکه های ۹۰ مگابایتی تقسیم بندی میشود مثلا اگر فایل شما ۳۰۰ مگابایت باشد باید ۴ عدد فایل دانلود شود و شما باید هر ۴ فایل را دانلود و سپس اکسترکت بکنید. برای اکسترکت کردن از 7zip استفاده کنید در لینوکس با دستور 7z x file.zip میتوانید همه ی فایل های تکه تکه را درون یک پوشه اکسترکت بکنید.
فایل اصلی دارای پسوند zip و پارت های دیگر دارای فرمت شماره گذاری شده به شکل z01 z02  و ... هستند. در ویندوز یا مک با نصب برنامه هایی مثل 7zip یا دیگر ابزارهای فشرده سازی میتوانید این فایلهای تکه تکه شده را یکجا اکسترکت بکنید.

---

## 🔔 بروزرسانی جدید: 

- امکان دسته بندی فایل های زیپ درون پوشه ها فراهم شد. اگر چندین فایل دانلود کنید و هر کدام به پارت های مختلف تقسیم بندی شوند این امکان بصورت اتوماتیک هر کدام را درون پوشه ای جدا دسته بندی میکند برای این امکان به بخش Actions رفته و روی گزینه ی Sort files بزنید و سپس گزینه ی run workflow را اجرا کنید.
- پاک کننده ی پوشه ی downloads اضافه شد در بخش Actions روی گزینه ی Clean download folder بزنید و سپس Run workflow را اجرا کنید تا پوشه ی downloads خالی شود.
- نام دانلودر در بخش Actions به Download from url تغییر پیدا کرده است.
- 🌐 مرورگر وب اضافه شد . برای استفاده از مرورگر به قسمت Actions روی گزینه ی browse web بزنید و سپس در قسمت run workflow ادرس سایت مقصد را بزنید. با این کار یک آرشیو با نام ادرس سایت و تاریخ آن لحظه ساخته میشود که درون آن اسکرین شات کامل صفحه به همراه فایل ها و لینک های صفحه قرار میگیره . همچنین فایل zip جهت دانلود در کنار پوشه ی تاریخ ساخته میشود که میتوانید یکجا دانلود کنید. یک فایل browse.md هم در مسیر اصلی ریپازیتوری اضافه میشود که شامل لیست تمام سایت هایی هست که دانلود کرده اید.


---

> راه های تکراری نتایج جدید رقم نمیزند. برای نتیجه ای جدید باید راهی جدید امتحان کرد

 
# <a href="https://avasam.ir/post/get-files-by-github" target="_blank" rel="do-follow follow sponsered">🔗 آموزش ویدیویی استفاده از این ابزار </a>

برای دریافت آموزش های بیشتر در پیام رسان بله عضو کانال ما باشید :‌
# 🔗 https://ble.ir/avasam_edu


موفق باشید.


---

---

---

---

---

---

---

---

---

---

## فایل های دانلود شده در گیتهاب شما :

1. [9d05fb968259c64fe6230394449db9074c37eb984f74be322d97a00494924237](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/9d05fb968259c64fe6230394449db9074c37eb984f74be322d97a00494924237)

2. [__belle_wise_and_cissia_zenless_zone_zero_drawn_by_croove_and_mia_seiyu_voice_actor__f5329d03c25c459fde481f071e5bdb35](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/__belle_wise_and_cissia_zenless_zone_zero_drawn_by_croove_and_mia_seiyu_voice_actor__f5329d03c25c459fde481f071e5bdb35)

3. [_gamma](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/_gamma)

4. [_star](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/_star)

5. [_sun](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/_sun)

6. [alice_thymefield_and_wise_zenless_zone_zero_drawn_by_misuzugon_voice_actor_and_redrain3d6f69b6ce0716ec4f23dc54a0f64ab0a7](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/alice_thymefield_and_wise_zenless_zone_zero_drawn_by_misuzugon_voice_actor_and_redrain3d6f69b6ce0716ec4f23dc54a0f64ab0a7)

7. [aria_zenless_zone_zero_drawn_by_ann1s_ebora_and_squishsuccubusb84dba38f52cb9ebf80bd993900549c5](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/aria_zenless_zone_zero_drawn_by_ann1s_ebora_and_squishsuccubusb84dba38f52cb9ebf80bd993900549c5)

8. [belle_and_cissia_zenless_zone_zero_drawn_by_kitsuneecchi_riizuwu_voice_actor_and_vicinekod7d68437b6e2f30f14e17d9f49483462](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/belle_and_cissia_zenless_zone_zero_drawn_by_kitsuneecchi_riizuwu_voice_actor_and_vicinekod7d68437b6e2f30f14e17d9f49483462)

9. [belle_and_nicole_demara_zenless_zone_zero_drawn_by_rougenine1bb2265a22485c36ec8cd29e03624e32](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/belle_and_nicole_demara_zenless_zone_zero_drawn_by_rougenine1bb2265a22485c36ec8cd29e03624e32)

10. [belle_and_vivian_banshee_zenless_zone_zero_drawn_by_kaikibooo_misuzugon_voice_actor_and_vixxen_voice_actor0717f08df45c59649f76c2d22e35b696](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/belle_and_vivian_banshee_zenless_zone_zero_drawn_by_kaikibooo_misuzugon_voice_actor_and_vixxen_voice_actor0717f08df45c59649f76c2d22e35b696)

11. [burnice_white_zenless_zone_zero_drawn_by_chiyo_voice_actor_dab_neko_delta_fxx_gemini_starsign_voice_actor_and_lewddmon_voice_actord9528cd3b75261f2d6689227046e3dc4](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/burnice_white_zenless_zone_zero_drawn_by_chiyo_voice_actor_dab_neko_delta_fxx_gemini_starsign_voice_actor_and_lewddmon_voice_actord9528cd3b75261f2d6689227046e3dc4)

12. [ellen_joe_zenless_zone_zero_drawn_by_moecodeb6a6eaabb99eca1a6864c10b3746e90c](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/ellen_joe_zenless_zone_zero_drawn_by_moecodeb6a6eaabb99eca1a6864c10b3746e90c)

13. [ellen_joe_zenless_zone_zero_drawn_by_starrymomokocff845466e87eaf9b047e44a3439eeaa](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/ellen_joe_zenless_zone_zero_drawn_by_starrymomokocff845466e87eaf9b047e44a3439eeaa)

14. [gAAAAABp-lQ4oCl-aHQM5C8HBeakjTERfJ3EWRYGyWRpPulM8O1oeYFAbiV-5oHHtB8PeYKqd0TeiAoJaWUEf_Pg-LWwYCR8CVhB3RGow6W6iq3vmPs8kC0RZmja-GYPJOvzsqRUpFe7Xh6k2RWV6uy1_rcfokyPjBHZylOQWu9ILK43D3Vz4-Q=](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/gAAAAABp-lQ4oCl-aHQM5C8HBeakjTERfJ3EWRYGyWRpPulM8O1oeYFAbiV-5oHHtB8PeYKqd0TeiAoJaWUEf_Pg-LWwYCR8CVhB3RGow6W6iq3vmPs8kC0RZmja-GYPJOvzsqRUpFe7Xh6k2RWV6uy1_rcfokyPjBHZylOQWu9ILK43D3Vz4-Q=)

15. [gAAAAABp-lRtc-iulAXObcfAC_AsG96GNe6EbyjHRJs8UR0iCI2_waBFRC0zT-MbTpWBqBp3HfUPNvhd9vpsnMEDRQ3m3J4dxSEIVA71QJKbnbadJ9dCYvaawfIxblE80Fe4rjJeBxLMiWkUdxi9fzQEDpRycDa7uOfDlPnkodaR4zHt96m6j1s=](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/gAAAAABp-lRtc-iulAXObcfAC_AsG96GNe6EbyjHRJs8UR0iCI2_waBFRC0zT-MbTpWBqBp3HfUPNvhd9vpsnMEDRQ3m3J4dxSEIVA71QJKbnbadJ9dCYvaawfIxblE80Fe4rjJeBxLMiWkUdxi9fzQEDpRycDa7uOfDlPnkodaR4zHt96m6j1s=)

16. [gAAAAABp-nDxQOUPt5ssPE8zh2Todpx7Np-D7zA8lYd7gcmvRkxT2ttNKdIV3SOd52QW_JoDkVCOOV50hHh7OJ6fi9-IVcoA03NVvx00ApzPoeuPlLc7NBROoHNR-ZP6SGXdNzOs_Al53nmT5Gx2K6SKA80xF6zlEG8JSMlS-m8WzglcUNqE9kc=](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/gAAAAABp-nDxQOUPt5ssPE8zh2Todpx7Np-D7zA8lYd7gcmvRkxT2ttNKdIV3SOd52QW_JoDkVCOOV50hHh7OJ6fi9-IVcoA03NVvx00ApzPoeuPlLc7NBROoHNR-ZP6SGXdNzOs_Al53nmT5Gx2K6SKA80xF6zlEG8JSMlS-m8WzglcUNqE9kc=)

17. [gAAAAABp-zNOXKIgFBk1Wf31yl6W8HcDCFrVHu60034hqp_7-MVr-uezEZSTE0FIfBRHvjCh9QKuF4CZO2ibF2vo_o873yvbzqAegxN0m_TKFgAvNTMXkNRdSvr9Shxn9SggA05N_n2k3RNjvWduG2cFy_cPo2iND-T00ClQbidezArCWZTAscY=](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/gAAAAABp-zNOXKIgFBk1Wf31yl6W8HcDCFrVHu60034hqp_7-MVr-uezEZSTE0FIfBRHvjCh9QKuF4CZO2ibF2vo_o873yvbzqAegxN0m_TKFgAvNTMXkNRdSvr9Shxn9SggA05N_n2k3RNjvWduG2cFy_cPo2iND-T00ClQbidezArCWZTAscY=)

18. [jane_doe_and_seth_lowell_zenless_zone_zero_drawn_by_dab_neko_redrain3d_and_ruby_red_voice_actor440b6e13d942e055b4ac96d3d0aebd1e](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/jane_doe_and_seth_lowell_zenless_zone_zero_drawn_by_dab_neko_redrain3d_and_ruby_red_voice_actor440b6e13d942e055b4ac96d3d0aebd1e)

19. [jane_doe_zenless_zone_zero_drawn_by_delights2s_thebredfactory_and_zorak_the_evil8117951ddb94fb5d8dfe01347715e3e0](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/jane_doe_zenless_zone_zero_drawn_by_delights2s_thebredfactory_and_zorak_the_evil8117951ddb94fb5d8dfe01347715e3e0)

20. [ju_fufu_zenless_zone_zero_drawn_by_dkclaude3dd6d655c7db47003894b7d8a7130c2c00](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/ju_fufu_zenless_zone_zero_drawn_by_dkclaude3dd6d655c7db47003894b7d8a7130c2c00)

21. [on-going](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/on-going)

22. [sweety_zenless_zone_zero_drawn_by_evil_trevo_fenryslewpiva_voice_actor_fitzyva_voice_actor_and_pointyaux84dbf80d43bee787f5ec9907e9d00366](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/sweety_zenless_zone_zero_drawn_by_evil_trevo_fenryslewpiva_voice_actor_fitzyva_voice_actor_and_pointyaux84dbf80d43bee787f5ec9907e9d00366)

23. [trailblazer_caelus_and_dialyn_zenless_zone_zero_drawn_by_imnotper7vertd57d93d58e9c3da9a6e0fe9e213fa2de](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/trailblazer_caelus_and_dialyn_zenless_zone_zero_drawn_by_imnotper7vertd57d93d58e9c3da9a6e0fe9e213fa2de)

24. [ukinami_yuzuha_zenless_zone_zero_drawn_by_lk_lk00_m_da_s_tarou_and_squishsuccubusdf3753af052c4d098476ad00f7618397](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/ukinami_yuzuha_zenless_zone_zero_drawn_by_lk_lk00_m_da_s_tarou_and_squishsuccubusdf3753af052c4d098476ad00f7618397)

25. [wise_and_yidhari_murphy_zenless_zone_zero_drawn_by_bewyx8d026fd7fce75ebbf2556eae4d688c7e](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/wise_and_yidhari_murphy_zenless_zone_zero_drawn_by_bewyx8d026fd7fce75ebbf2556eae4d688c7e)

26. [wise_sunna_nangong_yu_and_aria_zenless_zone_zero_drawn_by_sileter582503853558f99668b411f2cd67d944](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/wise_sunna_nangong_yu_and_aria_zenless_zone_zero_drawn_by_sileter582503853558f99668b411f2cd67d944)

27. [wise_ukinami_yuzuha_and_alice_thymefield_zenless_zone_zero_drawn_by_anno_morana_voice_actor_pincree_voice_actor_and_siletera529dbe74f2bdd114e5ce80d5c1da276](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/wise_ukinami_yuzuha_and_alice_thymefield_zenless_zone_zero_drawn_by_anno_morana_voice_actor_pincree_voice_actor_and_siletera529dbe74f2bdd114e5ce80d5c1da276)

28. [zhu_yuan_zenless_zone_zero_drawn_by_bluethebone_and_sharkmommyvt_voice_actor82b1440a456e3f798fba2e010ff13944](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/zhu_yuan_zenless_zone_zero_drawn_by_bluethebone_and_sharkmommyvt_voice_actor82b1440a456e3f798fba2e010ff13944)

29. [zhu_yuan_zenless_zone_zero_drawn_by_delights2s_and_invadernoodles_voice_actor5872593a96a58fc33cf0df520a7d8f62](https://github.com/genshinshiba9-star/Ahh-downloader/tree/main/downloads/zhu_yuan_zenless_zone_zero_drawn_by_delights2s_and_invadernoodles_voice_actor5872593a96a58fc33cf0df520a7d8f62)

---
