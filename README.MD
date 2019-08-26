Furthering HTML and CSS revision via FreeCodeCamp's Applied Accessibility resources and copying passed code to Git repo as I go through each task. Documenting below anything new I learn, or anything I am reminded of that I may have forgotten.

    - Learned proper use of Div, Article and section tags in relation to accessibility:
        -<div> - groups content
        - <section> - groups related content
        - <article> - groups independent, self-contained content
    - Learned use of audio element for hearing-impaired users.
        - Audio tags generally require controls attribute. Does not require quotes or tags; is a boolean. Example:
            <audio controls>
                <source src="http://www.audiosource.com/audio123" />
            </audio>