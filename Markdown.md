<html>
    <head>
        <style>
            @keyframes example {
                0%   {background-color:red; left:0px; top:0px;}
                25%  {background-color:yellow; left:200px; top:0px;}
                50%  {background-color:blue; left:200px; top:200px;}
                75%  {background-color:green; left:0px; top:200px;}
                100% {background-color:red; left:0px; top:0px;}
            }
            div {
                width: 100px;
                height: 100px;
                position: relative;
                background-color: red;
                animation-name: example;
                animation-duration: 4s;
            }
        </style>
    </head>
    <body>
        <h1>Markdown exercice:</h1>
            <h2>Ordered list</h2>
                <h3>
                    <ol>
                        <li>element 1</li>
                        <li>element 2</li>
                        <li>element 3</li>
                    </ol>
                </h3>
            <h2>Unordered list</h2>
                <h3>
                    <ul>
                        <li>element 1</li>
                        <li>element 2</li>
                        <ol>
                            <li>sub-element 1</li>
                            <li>This is the link to see Readme file:</li>
                                <a href="https://github.com/AIchrak/Git-training/blob/main/README.md">>>Click here<<</a>
                        </ol>
                    </ul>
                </h3>
                <h3>Here is an image:</h3>
                <img src="https://images.unsplash.com/photo-1587620962725-abab7fe55159?ixlib=rb-1.2.1&ixid=MnwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8&auto=format&fit=crop&w=1031&q=80" alt="computer">
            <div>This is an animated element!</div>
    </body>
</html>