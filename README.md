# Frequent-Used-Commands
Commands used frequently for my projects.

for http requests :
( Ref : https://www.kirupa.com/html5/making_http_requests_js.htm )

var xhr = new XMLHttpRequest();
xhr.open('GET', "https://ipinfo.io/json", true);
xhr.send();
 
xhr.onreadystatechange = processRequest;
 
function processRequest(e) {
 
}


# Add class to element:

document.getElementById('loading').classList.add("loading");

# Create element & append:

let ul = document.createElement('ul');
let li;
li = document.createElement('li');
li.appendChild(document.createTextNode('Sample Text'));
ul.appendChild(li);



https://api.themoviedb.org/3/trending/all/day?api_key=123

# Styles for this image

https://imgur.com/caCqUfD

    background-color: #2F3542;
    background-image: -webkit-linear-gradient(-72deg, #2f3542 50%, #ffffff 50%);
    border-radius: 8px;
    min-height: 250px;
    width: 500px;
    position: absolute;
    right: 0;
    top: 0;
    z-index: 1;
    
