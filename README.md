# QuizizzHelper
A little helper for online Quizizz

# How to use
Simply right click on bookmarks bar and select add page. Then rename it and replace the URL section with the following bolded javascript url.
To use, you just click on the bookmark. *You must do this twice for it to work.* Once on the start page [Looks like this](https://quizizz.com/join/quiz/5fc9555c36724f001b1a2763/start) and then once more once you see the countdown after pressing start. Or you could copy the javascript and paste it into the console (F12).

~~# Copy the following ~~
~~**javascript:fetch("https://raw.githubusercontent.com/BadWolf22/QuizizzHelper/main/quizizzGood.js").then((res) => res.text() .then((t) => eval(t)))**~~

# Copy the following
**javascript:(function(){window.s0=document.createElement('script');window.s0.setAttribute('type','text/javascript');window.s0.setAttribute('src','https://bookmarkify.it/bookmarklets/42033/raw');document.getElementsByTagName('body')[0].appendChild(window.s0);})();**
