### Hello Homies 👋
<!---
<div>
<img style="width:45%" src="http://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=sangvu1303&theme=dracula" alt="sangvu1303" />
<img style="width:45%" src="http://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=sangvu1303&theme=dracula&utcOffset=8" alt="sangvu1303" />
<br>
<img style="width:92%" src="http://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=sangvu1303&theme=dracula" alt="sangvu1303" />
</div>
--->

<h2 align="center">About me</h2>

```golang
package main

import (
	"fmt"
)

type Bio map[string]string

func main() {
	for k, v := range GetBio() {
		fmt.Printf("%+v: %+v\n", k, v)
	}
}

func GetBio() Bio {
	return Bio{
    " Name":             "Vũ Quang Sáng"
    " YoB":              "2000"
    " Home Town":        "Nam Định"
		" Collage":          "PTIT Hanoi",
		" Learning":         "C++,PYTHON,JAVA,HTML,CSS,JS,PHP,...",
		" Ask me about":     "Basic Web design",
    " My hobbies":       "Music,Singing,Drawing,Traveling,Motobike,PUBG,AOV,Sneaker,Fashion,Tobacco,Vape,..."
	}
}
```
