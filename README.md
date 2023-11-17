# تبلیغات داخل v2rayNG
مخزن تبلیغات شخصی ما
# چجوری ویرایش کنم؟
خب ما یه فایل `config.json` داریم توی این مخزن که باید اونو ویرایش کنیم.\
ساختار جیسون ما به این صورت هست:
```json
{
  "status": false,
  "text": "TEXT",
  "url": "https://LINK"
}
```
چیز هایی که ویرایش میشن.
| کلید   	| مقدار      	| توضیحات                                              	|
|--------	|------------	|------------------------------------------------------	|
| status 	| true/false 	| اگر کلید را فالس کنید تبلیغات غیرفعال میشود          	|
| text   	| string     	| متن اینجا قرار میگیره بهتره طولانی نباشه             	|
| url    	| string     	| اینجا باید لینک صفحه بازشو نوشته بشه همراه با پروتکل 	|
