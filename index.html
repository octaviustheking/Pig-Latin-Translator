<html>
    <head>
        <meta charset="utf-8">
        <style>
            h2.sub{
                color:white;
                width:100%;
                font-family: monospace;
                font-size:30px;
            }
            #input{
                color: black;
                width: 100%;
                font-family: monospace;
                color: white;
                font-size: 20px;
                background: darkgreen;
            }
            #selection{
                color: white;
                font-family: monospace;
                font-size: 17px;
                background: darkgreen;
            }
            #translate{
                font-family: monospace;
                font-size: 17px;
                color: white;
                background: darkgreen;
            }
            #output{
                color: white;
                width: 100%;
                font-family: monospace;
                font-size: 20px;
                background: darkgreen;
            }
            body{
                background: darkblue;
            }
        </style>
    </head>
    <body>
        <h2 class="sub">Pig Latin Translator</h2>
        <input id="input" type="text" value="Input">
        <br>
        <br>
        <select id="selection">
                    <option value="en-pglt" id="en-pglt">English to Pig Latin</option>
                    <option value="pglt-en" id="pglt-en">Pig Latin to English</option>
                </select>
        <br>
        <br>
        <button id="translate" type="button">Translate</button>
        <br>
        <br>
        <input id="output" type="text" value="This is where the translation will go" readonly>
        <script>
            var checkCap = function(t){
                var caps = "ABCDEFGHIJKLMNOPQRSTUVWXYZ";
                var lower = "abcdefghijklmnopqrstuvwxyz";
                for (var i = 0;i < caps.length;i++){
                    if (t === caps.substring(i,i+1)){
                        return(true);
                    }
                }
                for (var i = 0;i < lower.length;i++){
                    if (t === lower.substring(i,i+1)){
                        return(false);
                    }
                }
                return(undefined);
            };
            var makePigWordUpper = function(word,pos){
                var cap = checkCap(word.substring(pos,pos+1));
                if (cap){
                    var first = word.substring(0,1);
                    var second = word.substring(1,pos);
                    var third = word.substring(pos,pos+1);
                    var fourth = word.substring(pos+1,word.length);
                    first = first.toUpperCase();
                    third = third.toLowerCase();
                    var newWord = first+second+third+fourth;
                    return(newWord);
                }
                if (!cap){
                    return(word);
                }
            };
            var engToPglt = function(text){
                var words = [];
                var lastWordSep = 0;
                text = " " + text;
                text += " ";
                for (var i = 1;i <= text.length;i++){
                    if (text.substring(i,i+1) === " "){
                        words.push(text.substring(lastWordSep,i));
                        lastWordSep = i;
                    }
                }
                for (var i = 0;i < words.length;i++){
                    words[i] = words[i].substring(2,words[i].length)+words[i].substring(1,2)+"ay";
                    words[i] = makePigWordUpper(words[i],words[i].length-3);
                }
                return(words.join(" "));
            };
            var pgltToEng = function(text){
                var words = [];
                var lastWordSep = 0;
                text = " " + text;
                text += " ";
                for (var i = 1;i <= text.length;i++){
                    if (text.substring(i,i+1) === " "){
                        words.push(text.substring(lastWordSep,i));
                        lastWordSep = i;
                    }
                }
                for (var i = 0;i < words.length;i++){
                    if (words[i].substring(words[i].length-2,words[i].length) !== "ay"){
                        alert("This is not Pig Latin. It needs to be real Pig Latin for it to work");
                    }
                }
                for (var i = 0;i < words.length;i++){
                    words[i] = words[i].substring(words[i].length-3,words[i].length-2)+words[i].substring(1,words[i].length-3);
                    words[i] = makePigWordUpper(words[i],1);
                }
                return(words.join(" "));
            };
            var translate = document.getElementById("translate");
            var whenClicked = function(){
                var selection = document.getElementById("selection").value;
                var input = document.getElementById("input").value;
                var output = "";
                if (selection === "en-pglt"){
                    output = engToPglt(input);
                    output = makePigWordUpper(output,output.length-3);
                }
                if (selection === "pglt-en"){
                    output = pgltToEng(input);
                    output = makePigWordUpper(output,1);
                }
                document.getElementById("output").value = output;
            };
            var selection = document.getElementById("selection").value;
            translate.addEventListener("click", whenClicked);
        </script>
    </body>
</html>
