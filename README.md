- 👋 Hi, I’m @Dualpaz
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Dualpaz/Dualpaz is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import requests

url = "https://rabota.ykt.ru/?"
params = {"page": "3"}

response = requests.get(url, params=params)

# do something with the response, like parsing the HTML with BeautifulSoup
