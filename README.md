<a href="#"><img width="100%" height="auto" src="https://github.com/mnuddindev/mnuddindev/blob/main/banner.png" height="175px"/></a>

<div align="center">

# Hey, I'm MD NAZIM UDDIN 👋

### Backend Engineer | Go Developer | Security Enthusiast

![Profile Views](https://komarev.com/ghpvc/?username=mnuddindev&color=58A6FF&style=flat-square&label=Visitors)
![GitHub Followers](https://img.shields.io/github/followers/mnuddindev?label=Followers&style=flat-square&color=58A6FF&logo=github)
![GitHub Stars](https://img.shields.io/github/stars/mnuddindev?label=Stars&style=flat-square&color=FFA116&logo=github)

[![Open for Hire](https://img.shields.io/badge/💼_Open_for_Hire-Yes-00D9FF?style=for-the-badge)](mailto:inadislam@gmail.com)
[![Open Source](https://img.shields.io/badge/❤️_Open_Source-Contributor-FF6B6B?style=for-the-badge)](https://github.com/mnuddindev)
[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-Visit-4CAF50?style=for-the-badge)](https://inadislam.github.io/dev-portfolio)
[![Email](https://img.shields.io/badge/📧_Email-Contact-EA4335?style=for-the-badge)](mailto:inadislam@gmail.com)

```diff
+ Building scalable API with Go
+ Instead of Hunting bugs, Hunting jobs for now.
+ Building frontend using REACT
```

</div>

---
# $ whoami

```go
package main

import "fmt"

type BackendDeveloper struct {
	Name           string
	Role           string
	LanguageSpoken []string
	CurrentStack   []string
	Mindset        string
}

func NewBackendDeveloper(name, role, mindset string, languages, current_stack []string) *BackendDeveloper {
	return &BackendDeveloper{
		Name:           name,
		Role:           role,
		LanguageSpoken: languages,
		CurrentStack:   current_stack,
		Mindset:        mindset,
	}
}

func (bd *BackendDeveloper) SayHello() {
	fmt.Printf("Thanks for dropping by! I'm %s, a %s. Hope you find some of my work interesting.\n", bd.Name, bd.Role)
	fmt.Printf("I speak the following languages/locales: %v\n", bd.LanguageSpoken)
}

func main() {
	me := NewBackendDeveloper(
		"Md Nazim Uddin",
		"Backend Developer / Wordpress Developer",
		"Write code that doesn't suck. Ship fast. Break things. Fix them faster.",
		[]string{
			"bn_BD", "hi_IN", "en_US",
		},
		[]string{
			"Go", "JavaScript", "Python", "React",
		},
	)

	me.SayHello()
}
```
