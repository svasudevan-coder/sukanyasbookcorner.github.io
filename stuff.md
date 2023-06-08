header {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  padding: 30px 100px;
  display: flex;
  justify-content: space-between;
  align-items: center;
  /* doesnt allow images to interfere with hover functions */
  z-index: 10000;
}

header .l1 {
color: #49524b;
font-weight: 500;
/* removes link line undereath text */
text-decoration: none;
font-size:2em;
text-transform: uppercase;
letter-spacing: 1px;
}

/* arranges in a line instead of beneath each other  */
header ul {
  display: flex;
  justify-content: center;
  align-items: center;
}

header ul li {
/* removes bullet points that lists have automatically */
list-style: none;
/* evenly spaces out 'home' 'about me' 'contact' 'work' */
margin-left:20px;
}

header ul li a {
text-decoration: none;
padding: 6px 15px;
color: #49524b
}

/* , 
header ul li a.active, */
header ul li a:hover {
background: white;
color: #49524b;
border-radius: 20px;
} 