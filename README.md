# Javascript Challenge : "Data Visualisation"


    -repository : js-datavisualisation-challenge
    -mode: solo
    -type: consolidation challenge
    -duration: 5 days
    -author: Alexandre Plennevaux
    
![well](https://media.giphy.com/media/Lny6Rw04nsOOc/giphy.gif)

# Objectives

This consolidation challenge was supposed to help us assess our ability to solve a problem inspired from real-life situations using our new javascript muscles involving the following know-hows :

    DOM manipulation
    AJAX/FETCH request
    Using Third-party libraries
    problem-solving : design a logical solution to implement the expected result
    Debugging using the console
    Understand the notion of "separation of concerns"

# The mission
![007](https://media.giphy.com/media/nu4DN4nKos3m0/giphy.gif)

I work in the Multimedia department of one of the European Union institutions. This morning, Johnny Hasnoclew, the Project Manager, sends me on a mission: one of the in-house journalists has published a new article on the institution's website. The article in question is already integrated with an html / css / Javascript file.

He asks to make it more rich, more interactive

That's exactly what I am going to do, by adding two interactive data visualisation graphics using javascript. These graphs will be interactive in the sense that the user can manipulate the graph, such as filtering data, or reveal detailed data when the mouse hovers over it.

Evaluation

The evaluation method chosen is a self-evaluation based on the following indicators:
1. handling of the DOM:

    I was able to find the right selector to do it.
    I was able to inject the graph in the right place on the page via javascript.
    I was able to retrieve the html data in a format adapted to my javascript code.

2. Request ajax/fetch:

    I was able to receive the answer from the remote server in json.
    Then, I was able to build a callback function to process this data.

3. Use of third party libraries:

    I was able to integrate the third-party library into my application.
    I used the documentation provided by the library.
    I was able to generate the 2 inline data graphs.
    I was able to generate the "remote data" graph.

4. Problem-solving:

    Syntactic rigor: I was able to translate the processes I imagined into javascript syntax.
    Logical thinking: Through iterations and trial and error, I was able to find a logical path that works to address the issues raised by the client's request. Specifically:
        I was able to generate the 2 inline data graphs.
            I was able to generate the "remote data" graph.
        I was able to build a callback function to process remote data (received via ajax).
            I was able to make the realtime graph refresh in real time.
            I was able to display the detailed data when I hover the mouse.

5. Debugging:

    I use the console to understand what is happening and compare what I am trying to program with what the machine is doing.

6. Separation of concerns:

    If I disable javascript, the user experience is satisfactory, the user has access to data and content
    If I enable javascript, the tables are enhanced with an interactive graph.
