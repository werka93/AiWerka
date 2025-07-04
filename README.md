# AiWerka
Hi there
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Books</title>
</head>
<body>
    <header>
        <h1>A page about books &#128218;</h1>
        <p>By Anna, Laure and Weronika</p>
        <br>
        <nav>
            <a href="#about_us">About us</a>
            <a href="#favourite_reads">Our favourite reads</a>
            <a href="#facts">Quick book facts</a>
            <a href="#form">Share with us</a>
        </nav>
    </header>
​
    <main>
        <section id="about_us">
            <h2>About us</h2>
            <p>We're three HTML enthusiast who share a love for books. From sci-fi epics to heart-wrenching romances, stories shape how we see the world.</p>
            <p>On this page, you will find:
                <ul>
                    <li>Our personal top book lists</li>
                    <li>Short descriptions of our favorite reads</li>
                    <li>A table summarizing key facts about each book</li>
                    <li>A form for you to share your favorite books with us!</li>
                </ul>
                Whether you're a fellow bookworm or just looking for your next read — welcome!
            </p>
        </section>
        <section id="favourite_reads">
            <h2>Our favourite reads</h2>
            <div>
                <h3>&#128214; Laure's top 5 books</h3>
                <ol>
                    <li>A Discovery of Witches – Deborah Harkness</li>
                    <li>Dune – Frank Herbert</li>
                    <li>Me Before You – Jojo Moyes</li>
                    <li>Mr. Mercedes – Stephen King</li>
                    <li>Tales of the City – Armistead Maupin</li>
                </ol>
                <article>
                    <h4>Laure's take on reading</h4>
                    <q>I like a good read, whether it’s fantasy, romance, or a dark thriller — if the characters feel real and the story pulls me in, I’m hooked.</q>
                </article>
            </div>
        </section>
        <section id="facts">
            <h2>Quick book facts</h2>
            <table>
                <tr>
                    <th>Book title</th>
                    <th>Author</th>
                    <th>Genre</th>
                    <th>Year</th>
                    <th>One-sentence hook</th>
                </tr>
                <tr>
                    <td>A Discovery of Witches</td>
                    <td>Deborah Harkness</td>
                    <td>Fantasy</td>
                    <td>2011</td>
                    <td>A witch and a vampire unlock a magical manuscript's power.</td>
                </tr>
                <tr>
                    <td>Dune</td>
                    <td>Frank Herbert</td>
                    <td>Science Fiction</td>
                    <td>1965</td>
                    <td>Politics, prophecy, and sandworms in a galactic empire.</td>
                </tr>
                <tr>
                    <td>Me Before You</td>
                    <td>Jojo Moyes</td>
                    <td>Romance</td>
                    <td>2012</td>
                    <td>A young woman finds unexpected love while caregiving.</td>
                </tr>
                <tr>
                    <td>Mr. Mercedes</td>
                    <td>Stephen King</td>
                    <td>Thriller</td>
                    <td>2014</td>
                    <td>A retired detective hunts a deadly killer with a computer.</td>
                </tr>
                <tr>
                    <td>Tales of the City</td>
                    <td>Armistead Maupin</td>
                    <td>Fiction</td>
                    <td>1978</td>
                    <td>San Francisco in the ’70s — full of life, secrets, and joy.</td>
                </tr>
            </table>
            <aside>
                <h3>External recommendation</h3>
                <p>Looking for free classics to read online? Check out <a target="_blank" href="https://www.gutenberg.org/ebooks/">Project Gutenberg</a>: thousands of books, free to download or read in your browser.</p>
            </aside>
        </section>
        <section id="form">
            <h2>Share your favorite books with us!</h2>
            <p>We’d love to know what you enjoy reading! Fill out the form below and tell us about your top books.</p>
            <form action="/books">
                <div>
                    <label for="name">Your name:</label>
                    <input type="text" placeholder="enter your name" id="name" name="name">
                </div>
                <div>
                    <label for="email">You email address:</label>
                    <input type="email" placeholder="example@mail.com" id="email" name="email">
                </div>
                <div>
                    <label for="title">Your favourite book title:</label>
                    <input type="text" placeholder="enter the title of your favourite book" id="title" name="title">
                </div>
                <div>
                    <label for="reason">Why do you love it?</label>
                    <textarea name="reason" id="reason" placeholder="Tell us why you love this book"></textarea>
                </div>
                <div>
                    <label for="genre">What genre is it?</label>
                    <select name="genre" id="genre">
                        <option value="">--Please select an option--</option>
                        <option value="fantasy">Fantasy</option>
                        <option value="romance">Romance</option>
                        <option value="thriller">Thriller</option>
                        <option value="nonfiction">Non-fiction</option>
                        <option value="scifi">Science-Fiction</option>
                        <option value="fiction">Fiction</option>
                        <option value="crime">Crime</option>
                    </select>
                </div>
            </form>
            <button>Submit</button>
        </section>
    </main>
​
    <footer>
        <br>
        <p>Thanks for visiting our book-loving corner of the web. Happy reading, and don't forget to share your favorites!</p>
        <p>Page built with pure HTML for the HTML coding challenge 2025.</p>
    </footer>
</body>
</html>
​

