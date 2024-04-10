
```javascript
const data = async (api) => {
    try {
        const myCharacter = await fetch(api)
        
        myCharacter.push ({
            skills: 'html, css, js',
            age: 30,
            birthday: '30 April',
            start: '19 April 2023'
        })
    } catch (error) {
        alert('I am always learning')
    }
}
```
![HTML](https://img.shields.io/badge/HTML-orange) ![HTML](https://img.shields.io/badge/CSS-blue) ![HTML](https://img.shields.io/badge/JS-gold) ![HTML](https://img.shields.io/badge/Tailwind-blueviolet)


