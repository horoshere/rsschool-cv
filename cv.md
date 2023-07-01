 # Nikolay Eremeev
 ## Junior Frontend Developer
 ### Contact information
 * phone: +7 915 154 82 84
 * e-mail: nikolayeremeev@internet.ru
 * telegram: @zbrmn
 * github page: [horoshere](https://github.com/horoshere)

 ### About me
I work as an Avitologist. I have the skill to analyze a large amount of information. I am reliable and responsible, I am a team player.
I know I'm capable of more. It is in my interests to develop myself throughout my life. My goal is to become a quality front-end developer.
 ### Skills
 * HTML
 * CSS (SASS/SCSS, BEM, Bootstrap)
 * JavaScript
 * React JS (class components)
 * Git
 * Figma
 ### Code example
 *example of one simple react class component*:
 ```javascript
    const MovieList = ({data}) => {

        const element = data.map(item => {
            return (
                <Movie 
                key={item.id}
                id={item.id}
                title={item.title}
                year={item.year}
                summary={item.summary}
                poster={item.medium_cover_image}
                genres={item.genres}
                rating={item.rating}
                bigPoster={item.large_cover_image} />
            )
        });

        return (
            <ul className="movies">
                {element}
            </ul>
        )
    }
```

### Projects
* [marvel-app](https://horoshere.github.io/marvel-app/) - study project, React JS
* [movie-catalog-app](https://horoshere.github.io/movie-catalog-app/) - pet project, React JS
* [whoWillPlay](https://github.com/horoshere/whoWillPlay) - my first pet project, JavaScript


### Education
* Moscow State University of Food Production
    * Informatics and computer engineering
* Udemy
    * HTML/CSS
    * JavaScript + React (in progress)
    * RS Schools Course «JavaScript/Front-end. Stage 0» (in progress)

### Languages
* Russian - native speaker
* English - A2

