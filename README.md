/* ===== Global Styles ===== */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: 'Poppins', sans-serif;
}

body {
  color: #333;
  line-height: 1.6;
}

/* ===== Header & Navigation ===== */
header {
  background-color: #fff;
  box-shadow: 0 2px 5px rgba(0,0,0,0.1);
  padding: 10px 40px;
}

nav {
  display: flex;
  justify-content: space-between;
  align-items: center;
}

nav img {
  width: 100px;
}

nav ul {
  display: flex;
  list-style: none;
  gap: 30px;
}

nav ul li a {
  text-decoration: none;
  color: #333;
  font-weight: 600;
  transition: color 0.3s;
}

nav ul li a:hover {
  color: #ff5a5f;
}

/* ===== Hero Section ===== */
main section:first-of-type {
  text-align: center;
  padding: 80px 20px;
  background: #fefefe;
}

main section:first-of-type h1 {
  font-size: 3rem;
  margin-bottom: 20px;
  color: #111;
}

main section:first-of-type span {
  margin: 0 10px;
  font-weight: bold;
  color: #ff5a5f;
}

main section:first-of-type button {
  display: block;
  margin: 30px auto 0;
  background-color: #ff5a5f;
  color: #fff;
  border: none;
  padding: 12px 25px;
  font-size: 1rem;
  border-radius: 25px;
  cursor: pointer;
  transition: background 0.3s;
}

main section:first-of-type button:hover {
  background-color: #e04d53;
}

/* ===== Learn from Pros ===== */
main section:first-of-type div:last-child {
  margin-top: 60px;
}

main section:first-of-type div:last-child h2 {
  margin-bottom: 40px;
}

main section:first-of-type div:last-child > div {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 30px;
  justify-items: center;
}

main section:first-of-type div:last-child > div div {
  text-align: center;
}

main section:first-of-type div:last-child img {
  width: 100px;
  border-radius: 50%;
}

/* ===== Testimonial Section ===== */
main section:nth-of-type(2) {
  display: flex;
  flex-wrap: wrap;
  align-items: center;
  justify-content: center;
  padding: 60px 20px;
  background-color: #fafafa;
  gap: 40px;
}

main section:nth-of-type(2) img {
  max-width: 250px;
  border-radius: 10px;
}

main section:nth-of-type(2) blockquote {
  font-style: italic;
  color: #555;
  margin-bottom: 15px;
}

main section:nth-of-type(2) h3 {
  color: #ff5a5f;
}

/* ===== Tutorials Section ===== */
main section:nth-of-type(3) {
  text-align: center;
  padding: 80px 20px;
}

main section:nth-of-type(3) h2 {
  margin-bottom: 40px;
}

main section:nth-of-type(3) > div {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 40px;
}

main section:nth-of-type(3) > div > img {
  width: 100%;
  border-radius: 15px;
}

main section:nth-of-type(3) .fa-star {
  color: gold;
}

/* ===== Membership Section ===== */
main section:nth-of-type(4) {
  text-align: center;
  background-color: #fdfdfd;
  padding: 80px 20px;
}

main section:nth-of-type(4) h2 {
  margin-bottom: 40px;
}

main section:nth-of-type(4) > div {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
  gap: 30px;
  margin-bottom: 40px;
}

main section:nth-of-type(4) img {
  width: 60px;
  margin-bottom: 10px;
}

main section:nth-of-type(4) button {
  background-color: #ff5a5f;
  color: #fff;
  border: none;
  padding: 12px 25px;
  border-radius: 25px;
  cursor: pointer;
  font-size: 1rem;
  transition: background 0.3s;
}

main section:nth-of-type(4) button:hover {
  background-color: #e04d53;
}

/* ===== FAQ Section ===== */
main section:nth-of-type(5) {
  padding: 80px 20px;
}

main section:nth-of-type(5) h2 {
  text-align: center;
  margin-bottom: 40px;
}

main section:nth-of-type(5) > div {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 30px;
}

main section:nth-of-type(5) h3 {
  margin-bottom: 10px;
  color: #ff5a5f;
}

main section:nth-of-type(5) div div {
  margin-bottom: 20px;
  color: #555;
}

/* ===== Footer ===== */
footer {
  background-color: #222;
  color: #fff;
  padding: 40px 20px;
  text-align: center;
}

footer img {
  width: 100px;
  margin-bottom: 15px;
}

footer i {
  margin: 0 10px;
  color: #fff;
  cursor: pointer;
  transition: color 0.3s;
}

footer i:hover {
  color: #ff5a5f;
}

footer p {
  margin-top: 20px;
  font-size: 0.9rem;
  color: #aaa;
}

/* ===== Responsive Design ===== */
@media (max-width: 768px) {
  nav ul {
    gap: 15px;
  }

  main section:first-of-type h1 {
    font-size: 2rem;
  }

  main section:nth-of-type(2) {
    flex-direction: column;
  }
}
