<html lang="en">
<head>

    <title>reveal.js - The HTML Presentation Framework</title>

</head>

<body style="transition: -webkit-transform 0.8s ease; -webkit-transition: -webkit-transform 0.8s ease;">

    <div class="reveal default center" data-transition-speed="default" data-background-transition="default">

        <!-- Any section element inside of this container is displayed as a slide -->
        <div class="slides" style="width: 960px; height: 700px; zoom: 0.2;">
            <section data-charset="iso-8859-15" data-markdown  class="present" style="top: -310px; display: block;">

# Ionic

                    Samyak Bhuta <!-- -->

                    email : <!-- -->
                    [samyak dot bhuta at gmail.com](mailto:samyak.bhuta@gmail.com) <!-- -->

                    twitter : <!-- -->
                    [@samyak_bhuta](https://twitter.com/samyak_bhuta) <!-- -->

                    github : <!-- -->
                    [samyakbhuta](https://github.com/samyakbhuta) <!-- -->

            </section>
            <section data-charset="iso-8859-15" data-markdown class="future" style="top: -95px; display: block;" hidden="">

### Official Site

*   [](http://ionicframework.com)[http://ionicframework.com](http://ionicframework.com)
            </section>
            <section data-charset="iso-8859-15" hidden="" class="stack future" style="top: 0px; display: block;" data-previous-indexv="0">
                <section data-markdown style="top: -127.5px; display: block;">

### Ionic is what ?

                    > The beautiful, open source front-end SDK for developing hybrid mobile apps with HTML5.
                </section><section data-markdown class="future" style="top: -175px; display: block;">

### Ionic is what ?

*   An opinionated mobile application development framework on top of Cordova
*   This means it is going to be a hybrid mobile application
*   The other opinionated part is it's selection of Angular.js
*   It's own CSS framework (which is not Bootstrap or ZURB's Foundation)
                </section>
            </section>
            <section data-charset="iso-8859-15" hidden="" class="stack future" style="top: 0px; display: block;" data-previous-indexv="0">
                <section data-markdown style="top: -135px; display: block;">

### Installing Ionic

*   You need to have node.js installed as a prerequisite
*   Get yourself node.js from [](http://nodejs.org/download/)[http://nodejs.org/download/](http://nodejs.org/download/)
                </section><section data-markdown class="future" style="top: -105px; display: none;">

### Install Cordova

    <span class="comment">npm</span> <span class="comment">install</span> <span class="literal">-</span><span class="comment">g</span> <span class="comment">cordova</span>`</pre>
                    </section><section data-markdown class="future" style="top: -20px; display: none;">

    ### Install Ionic

    <pre>`<span class="comment">npm</span> <span class="comment">install</span> <span class="literal">-</span><span class="comment">g</span> <span class="comment">ionic</span>`</pre>
                    </section>
                </section>
                <section data-charset="iso-8859-15" hidden="" class="stack future" style="top: 0px; display: block;" data-previous-indexv="0">
                    <section data-markdown style="top: -145px; display: block;">

    ### Creating a Hello World Application

    <pre>`<span class="title">ionic</span> start hello-world`</pre>

*   It will create an ionic application with necessary boilerplat'ing
                    </section><section data-markdown class="future" style="top: -145px; display: block;">

    ### Dig in to the application folder

    <pre>`<span class="built_in">cd</span> hello-world`</pre>

*   You may want to look around and explore the folders here.
*   It is a essentially a `Cordova` project.
                    </section><section data-markdown class="future" style="top: -145px; display: block;">

    ### Setup few more things - saas

    <pre>`<span class="title">ionic</span> setup sass`</pre>

*   `Sass` is a CSS on steroids. Learn more [here](http://sass-lang.com)
*   This step is optional, you may want to have your project not use `Saas`.
                    </section><section data-markdown class="future" style="top: -150px; display: block;">

    ### Check it in browser

    <pre>`<span class="title">ionic</span> serve`</pre>

    This should start a server and automatically open the app in your default browser

                    </section><section data-markdown class="future" style="top: -20px; display: none;">

    ### Try it on Mobile Browsers

*   At this moment it would be good idea to try this served application in your mobile browsers, too.
*   It would help you understand how the application will look and feel
*   You might be able to also gauge if the performance and responsiveness is acceptable or not
                    </section><section data-markdown class="future" style="top: -20px; display: none;">

    ### Time to see it as an Application

*   First, you need to add respective platform
*   Build for that platform
*   See it on emulator
*   Run it on real device
                    </section><section data-markdown class="future" style="top: -20px; display: none;">

    ### Adding platform

    <pre>`ionic platform <span class="keyword">add</span> ios`</pre>

*   Will add `iOS` as target platform
*   You need to run this command only once to allow `ionic` to prepare for the target platform
                    </section><section data-markdown class="future" style="top: -20px; display: none;">

    ### Building for the platform

    <pre>`<span class="title">ionic</span> build ios`</pre>

*   Will compile and build for the platform
*   Need to repeat this every time you change something in code or configuration
                    </section><section data-markdown class="future" style="top: -20px; display: none;">

    ### Go for a (virtual!) ride

    <pre>`<span class="title">ionic</span> emulate ios`</pre>

*   Will start the respective emulator and allow you to test the application
*   Needless to say, you need to execute this command everytime you want to see application in action
                    </section><section data-markdown class="future" style="top: -20px; display: none;">

    ### Run it in your devices

    <pre>`ionic <span class="command">run</span> ios`</pre>

*   Launch the application in the connected device
*   If the device is not recognised, it will launch it in emulator
                    </section><section data-markdown class="future" style="top: -20px; display: none;">

    ### More init powers - Please try

    <pre>`<span class="title">ionic</span> start hello-world-<span class="number">2</span> blank`</pre>
    <pre>`<span class="title">ionic</span> start hello-world-<span class="number">3</span> tabs`</pre>
    <pre>`ionic start hello<span class="attribute">-world</span><span class="attribute">-with</span><span class="attribute">-sidemenu</span> sidemenu

*   It will not only create the application but populate it with some generated code
*   Basically, it is boilerplat'ing to next level
                </section>
            </section>
            <section data-charset="iso-8859-15" hidden="" class="stack future" style="top: 0px; display: block;" data-previous-indexv="0">
                <section data-markdown style="top: -135px; display: block;">

### Using Ionic Creator

*   Please go to [](https://creator.ionic.io/)[https://creator.ionic.io/](https://creator.ionic.io/)
*   Sign up !
                </section><section data-markdown class="future" style="top: -167.5px; display: block;">

### What is Ionic Creator ?

                    > Creator makes it easy to rapidly build Ionic mobile apps. With a drag-and-drop interface and real code exporting, you can create live apps for your team with a few drags of the mouse. And it's totally free to use.
                </section><section data-markdown class="future" style="top: -115px; display: block;">

### Mind you - It is in Beta !

*   But it is already awesome
                </section><section data-markdown class="future" style="top: -135px; display: none;">

### Create a small app

*   Try to create some small application using the controls provided by Creator
*   Checkout export functionality, with which you can download the application and build it locally
                </section><section data-markdown class="future" style="top: -20px; display: none;">

### Some Inspiration

*   [](http://showcase.ionicframework.com)[http://showcase.ionicframework.com](http://showcase.ionicframework.com)
                </section>
            </section>
            <section data-charset="iso-8859-15" data-markdown hidden="" class="future" style="top: -110px; display: block;">

# Thank you

            </section>
        </div>

        <div class="backgrounds"><div class="slide-background present"></div><div class="slide-background future"></div><div class="slide-background future"><div class="slide-background present"></div><div class="slide-background future"></div></div><div class="slide-background future"><div class="slide-background present"></div><div class="slide-background future"></div><div class="slide-background future"></div></div><div class="slide-background future"><div class="slide-background present"></div><div class="slide-background future"></div><div class="slide-background future"></div><div class="slide-background future"></div><div class="slide-background future"></div><div class="slide-background future"></div><div class="slide-background future"></div><div class="slide-background future"></div><div class="slide-background future"></div><div class="slide-background future"></div><div class="slide-background future"></div></div><div class="slide-background future"><div class="slide-background present"></div><div class="slide-background future"></div><div class="slide-background future"></div><div class="slide-background future"></div><div class="slide-background future"></div></div><div class="slide-background future"></div></div><div class="progress" style="display: block;"><span style="width: 0px;"></span></div><aside class="controls" style="display: block;"><div class="navigate-left"></div><div class="navigate-right enabled fragmented"></div><div class="navigate-up"></div><div class="navigate-down"></div></aside><div class="slide-number"></div><div class="state-background"></div><div class="pause-overlay"></div>
    </div>

</body>
</html>