# 💻 08. API's uitlezen > oefening 05

## 🛠️ opdrachten

Tijdens dit labo leer je
 - gebruik maken van een API-sleutel voor toegang.

### Postman opstarten

 - Start Postman.

### authentificatie met api key

 - [API: News API](https://newsapi.org)
 - endpoint: /top-headlines

---

1. Maak een nieuw verzoek naar de API.
GET
2. Gebruik de endpoint /top-headlines.
https://newsapi.org/v2/top-headlines?category=business
3. Voeg een X-Api-Key header toe met je API-sleutel.
In postman volgende value gezet onder tab authorization: 
Key: X-Api-Key
Value: "Persoonlijke string ingegeven"
Add to: header
4. Voer het verzoek uit en bekijk de respons.
Respons:
{
    "status": "ok",
    "totalResults": 1000,
    "articles": [
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Portafolio",
            "title": "Bancos pequeños de EE. UU. se crecen al financiar petroleras y carboneras - Portafolio",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiemh0dHBzOi8vd3d3LnBvcnRhZm9saW8uY28vZWNvbm9taWEvZmluYW56YXMvYmFuY29zLXBlcXVlbm9zLWRlLWVlLXV1LXNlLWNyZWNlbi1hbC1maW5hbmNpYXItcGV0cm9sZXJhcy15LWNhcmJvbmVyYXMtNjAzMTgy0gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T14:33:29Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "infobae",
            "title": "“Somos nerds de la energía”: la gente está obsesionada con los aparatos eléctricos domésticos - infobae",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMigwFodHRwczovL3d3dy5pbmZvYmFlLmNvbS93YXBvLzIwMjQvMDQvMjAvc29tb3MtbmVyZHMtZGUtbGEtZW5lcmdpYS1sYS1nZW50ZS1lc3RhLW9ic2VzaW9uYWRhLWNvbi1sb3MtYXBhcmF0b3MtZWxlY3RyaWNvcy1kb21lc3RpY29zL9IBlwFodHRwczovL3d3dy5pbmZvYmFlLmNvbS93YXBvLzIwMjQvMDQvMjAvc29tb3MtbmVyZHMtZGUtbGEtZW5lcmdpYS1sYS1nZW50ZS1lc3RhLW9ic2VzaW9uYWRhLWNvbi1sb3MtYXBhcmF0b3MtZWxlY3RyaWNvcy1kb21lc3RpY29zLz9vdXRwdXRUeXBlPWFtcC10eXBl?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T14:10:02Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "OÖNachrichten",
            "title": "Shoppingcenter stehen bei Expansion auf der Bremse - OÖNachrichten",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMicWh0dHBzOi8vd3d3Lm5hY2hyaWNodGVuLmF0L21laW5lLXdlbHQvd29obmVuL3Nob3BwaW5nY2VudGVyLXN0ZWhlbi1iZWktZXhwYW5zaW9uLWF1Zi1kZXItYnJlbXNlO2FydDE2ODA3NiwzOTQxMjA30gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T14:00:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "CNN en Español",
            "title": "La nueva torre de 62 pisos que transformará el horizonte de la ciudad de Nueva York - CNN en Español",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiRWh0dHBzOi8vY25uZXNwYW5vbC5jbm4uY29tLzIwMjQvMDQvMjAvdG9ycmUtNjItcGlzb3MtbnVldmEteW9yay10cmF4L9IBSWh0dHBzOi8vY25uZXNwYW5vbC5jbm4uY29tLzIwMjQvMDQvMjAvdG9ycmUtNjItcGlzb3MtbnVldmEteW9yay10cmF4L2FtcC8?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T13:36:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "InfoMoney",
            "title": "Bitcoin: “halving” é concluído e traz ameaça a mineradores - InfoMoney",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiY2h0dHBzOi8vd3d3LmluZm9tb25leS5jb20uYnIvb25kZS1pbnZlc3Rpci9iaXRjb2luLWhhbHZpbmctZS1jb25jbHVpZG8tZS10cmF6LWFtZWFjYS1hLW1pbmVyYWRvcmVzL9IBZ2h0dHBzOi8vd3d3LmluZm9tb25leS5jb20uYnIvb25kZS1pbnZlc3Rpci9iaXRjb2luLWhhbHZpbmctZS1jb25jbHVpZG8tZS10cmF6LWFtZWFjYS1hLW1pbmVyYWRvcmVzL2FtcC8?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T13:24:37Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Cointelegraph en Español (Noticias sobre Bitcoin, Blockchain y el futuro del dinero)",
            "title": "Usuarios de Bitcoin gastan USD 2.4M en tasas en el bloque del halving - Cointelegraph en Español (Noticias sobre Bitcoin, Blockchain y el futuro del dinero)",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMibWh0dHBzOi8vZXMuY29pbnRlbGVncmFwaC5jb20vbmV3cy9iaXRjb2luLWhhbHZpbmctdXNlcnMtc3BlbmQtcmVjb3JkLW1pbGxpb25zLWJsb2NrLXNwYWNlLXJ1bmVzLXJhcmUtc2F0b3NoaXPSAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T13:20:57Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Forbes Austria",
            "title": "Ein Investment mit Weitblick - Forbes Austria",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiP2h0dHBzOi8vd3d3LmZvcmJlcy5hdC9hcnRpa2VsL2Vpbi1pbnZlc3RtZW50LW1pdC13ZWl0YmxpY2suaHRtbNIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T13:20:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "infobae",
            "title": "Una automotriz se convirtió en la primera en vender autos que no requieren vigilancia del conductor en EEUU - infobae",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMingFodHRwczovL3d3dy5pbmZvYmFlLmNvbS9lc3RhZG9zLXVuaWRvcy8yMDI0LzA0LzIwL3VuYS1hdXRvbW90cml6LXNlLWNvbnZpcnRpby1lbi1sYS1wcmltZXJhLWVuLXZlbmRlci1hdXRvcy1xdWUtbm8tcmVxdWllcmVuLXZpZ2lsYW5jaWEtZGVsLWNvbmR1Y3Rvci1lbi1lZXV1L9IBsgFodHRwczovL3d3dy5pbmZvYmFlLmNvbS9lc3RhZG9zLXVuaWRvcy8yMDI0LzA0LzIwL3VuYS1hdXRvbW90cml6LXNlLWNvbnZpcnRpby1lbi1sYS1wcmltZXJhLWVuLXZlbmRlci1hdXRvcy1xdWUtbm8tcmVxdWllcmVuLXZpZ2lsYW5jaWEtZGVsLWNvbmR1Y3Rvci1lbi1lZXV1Lz9vdXRwdXRUeXBlPWFtcC10eXBl?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T13:12:28Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "APA OTS",
            "title": "Automation Anywhere erhält 2024 Great Place To Work Certification™ - APA OTS",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMie2h0dHBzOi8vd3d3Lm90cy5hdC9wcmVzc2VhdXNzZW5kdW5nL09UU18yMDI0MDQyMF9PVFMwMDI5L2F1dG9tYXRpb24tYW55d2hlcmUtZXJoYWVsdC0yMDI0LWdyZWF0LXBsYWNlLXRvLXdvcmstY2VydGlmaWNhdGlvbtIBL2h0dHBzOi8vd3d3Lm90cy5hdC9hbXAvcHIvT1RTXzIwMjQwNDIwX09UUzAwMjkv?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T13:02:18Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "اليوم السابع",
            "title": "سعر الجنيه الذهب في مصر .. تطورات جديدة في الأسواق - اليوم السابع",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMioAJodHRwczovL3d3dy55b3VtNy5jb20vc3RvcnkvMjAyNC80LzIwLyVEOCVCMyVEOCVCOSVEOCVCMS0lRDglQTclRDklODQlRDglQUMlRDklODYlRDklOEElRDklODctJUQ4JUE3JUQ5JTg0JUQ4JUIwJUQ5JTg3JUQ4JUE4LSVEOSU4MSVEOSU4QS0lRDklODUlRDglQjUlRDglQjEtJUQ4JUFBJUQ4JUI3JUQ5JTg4JUQ4JUIxJUQ4JUE3JUQ4JUFBLSVEOCVBQyVEOCVBRiVEOSU4QSVEOCVBRiVEOCVBOS0lRDklODElRDklOEEtJUQ4JUE3JUQ5JTg0JUQ4JUEzJUQ4JUIzJUQ5JTg4JUQ4JUE3JUQ5JTgyLzY1NTA1ODLSAZwCaHR0cHM6Ly9tLnlvdW03LmNvbS9hbXAvMjAyNC80LzIwLyVEOCVCMyVEOCVCOSVEOCVCMS0lRDglQTclRDklODQlRDglQUMlRDklODYlRDklOEElRDklODctJUQ4JUE3JUQ5JTg0JUQ4JUIwJUQ5JTg3JUQ4JUE4LSVEOSU4MSVEOSU4QS0lRDklODUlRDglQjUlRDglQjEtJUQ4JUFBJUQ4JUI3JUQ5JTg4JUQ4JUIxJUQ4JUE3JUQ4JUFBLSVEOCVBQyVEOCVBRiVEOSU4QSVEOCVBRiVEOCVBOS0lRDklODElRDklOEEtJUQ4JUE3JUQ5JTg0JUQ4JUEzJUQ4JUIzJUQ5JTg4JUQ4JUE3JUQ5JTgyLzY1NTA1ODI?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:48:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "الجريدة",
            "title": "لعشاق القوة الفرنسية.. سيارة بيجو 2008 موديل 2024 أسد هتسد معاك في أي مكان تروحه - الجريدة",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMi4gFodHRwczovL3d2dy5qYXJpZGEub25sLzIwNzM0LyVEOSU4NCVEOCVCOSVEOCVCNCVEOCVBNyVEOSU4Mi0lRDglQTclRDklODQlRDklODIlRDklODglRDglQTktJUQ4JUE3JUQ5JTg0JUQ5JTgxJUQ4JUIxJUQ5JTg2JUQ4JUIzJUQ5JThBJUQ4JUE5LSVEOCVCMyVEOSU4QSVEOCVBNyVEOCVCMSVEOCVBOS0lRDglQTglRDklOEElRDglQUMlRDklODgtMjAwOC0lRDklODUlRDklODglRDglQUYlRDklOEEv0gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:34:52Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "ECOticias.com",
            "title": "El motor de hidrógeno a presión que lo cambia todo: adiós a la gasolina y una potencia inédita - ECOticias.com",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiQ2h0dHBzOi8vd3d3LmVjb3RpY2lhcy5jb20vaG95ZWNvL21vdG9yLWRlLWhpZHJvZ2Vuby1hLXByZXNpb24vNTI5OS_SAQA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:30:46Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "OÖNachrichten",
            "title": "Fit für Schlamm und kleine Familie: Zweites Facelift für Suzuki Vitara - OÖNachrichten",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiiwFodHRwczovL3d3dy5uYWNocmljaHRlbi5hdC9wYW5vcmFtYS9tb3Rvcm1hcmt0L21vdG9yL2ZpdC1mdWVyLXNjaGxhbW0tdW5kLWtsZWluZS1mYW1pbGllLXp3ZWl0ZXMtZmFjZWxpZnQtZnVlci1zdXp1a2ktdml0YXJhO2FydDExMSwzOTQwMzky0gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:26:00Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Www.ce.cn"
            },
            "author": "锟斤拷锟斤拷锟斤拷",
            "title": "财经聚焦丨从广交会看外商在华支付便利化 - 中国经济网",
            "description": null,
            "url": "http://www.ce.cn/xwzx/gnsz/gdxw/202404/20/t20240420_38977253.shtml",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:25:00Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Andro4all",
            "title": "Logran la obtención de hidrógeno verde asequible y no-contaminante. Nos acerca al coche de hidrógeno - Andro4all",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMikgFodHRwczovL3d3dy5sYXZhbmd1YXJkaWEuY29tL2FuZHJvNGFsbC9jaWVuY2lhL2xvZ3Jhbi1sYS1vYnRlbmNpb24tZGUtaGlkcm9nZW5vLXZlcmRlLWFzZXF1aWJsZS15LW5vLWNvbnRhbWluYW50ZS1ub3MtYWNlcmNhLWFsLWNvY2hlLWRlLWhpZHJvZ2Vub9IBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:15:28Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "FRANCE 24 Español",
            "title": "Histórica victoria sindical entre trabajadores de Volkswagen en Tennessee, EEUU - FRANCE 24 Español",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiiAFodHRwczovL3d3dy5mcmFuY2UyNC5jb20vZXMvbWludXRvLWEtbWludXRvLzIwMjQwNDIwLWhpc3QlQzMlQjNyaWNhLXZpY3RvcmlhLXNpbmRpY2FsLWVudHJlLXRyYWJhamFkb3Jlcy1kZS12b2xrc3dhZ2VuLWVuLXRlbm5lc3NlZS1lZXV10gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:09:06Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "Andro4all",
            "title": "El Xiaomi SU7 protagoniza su primer accidente contra un Mercedes-Benz: así ha quedado el coche de Xiaomi - Andro4all",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMilQFodHRwczovL3d3dy5sYXZhbmd1YXJkaWEuY29tL2FuZHJvNGFsbC94aWFvbWkvZWwteGlhb21pLXN1Ny1wcm90YWdvbml6YS1zdS1wcmltZXItYWNjaWRlbnRlLWNvbnRyYS11bi1tZXJjZWRlcy1iZW56LWFzaS1oYS1xdWVkYWRvLWVsLWNvY2hlLWRlLXhpYW9tadIBAA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:01:48Z",
            "content": null
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "王志郁Plus",
            "title": "全球政局動盪資產保全成首選?! 美債大跌抄底短套將笑到最後?!｜20240420｜@inewsplus - 王志郁Plus",
            "description": null,
            "url": "https://news.google.com/rss/articles/CCAiC3JOY0pWTGEtOHd3mAEB?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:00:49Z",
            "content": null
        },
        {
            "source": {
                "id": null,
                "name": "Cctv.com"
            },
            "author": "邢斯馨",
            "title": "一季度多项交通运输指标创新高 - 央视网",
            "description": "一季度，我国民航全行业共完成运输总周转量349.3亿吨公里，同比增长45.6%。",
            "url": "https://jingji.cctv.com/2024/04/20/ARTIzH7wD1W1P7X8FCoMVWj7240420.shtml",
            "urlToImage": "//p3.img.cctvpic.com/photoAlbum/templet/common/DEPA1618991691963959/jingji.jpg",
            "publishedAt": "2024-04-20T12:00:00Z",
            "content": "349.345.6%\r\n1.837.7%1412201978%\r\n200.734.4%\r\n1048615.5%10.141114.728.5%123062091.6898.3"
        },
        {
            "source": {
                "id": "google-news",
                "name": "Google News"
            },
            "author": "AAzdravi.cz",
            "title": "Všechen prach ze žaluzií okamžitě zmizí. Je to dokonalé, jinak už to dělat nebudu - AAzdravi.cz",
            "description": null,
            "url": "https://news.google.com/rss/articles/CBMiaGh0dHBzOi8vd3d3LmFhemRyYXZpLmN6L3ZzZWNoZW4tcHJhY2gtemUtemFsdXppaS1va2Fteml0ZS16bWl6aS1qZS10by1kb2tvbmFsZS1qaW5hay11ei10by1kZWxhdC1uZWJ1ZHUv0gEA?oc=5",
            "urlToImage": null,
            "publishedAt": "2024-04-20T12:00:00Z",
            "content": null
        }
    ]
}