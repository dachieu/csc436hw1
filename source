<!DOCTYPE html>
<html>

<head>
    <title>Page Title</title>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
</head>

<body>
    <div class="root-container">
        <div class="header">
            <button id="reverse"> 
                REVERSE
            </button>
            <button id="remove-symbols-numbers"> 
                REMOVE SYMBOLS & NUMBERS
            </button>
            <button id="sort-alphabetically"> 
                SORT ALPHABETICALLLY
            </button>
            <button id="toggle-color"> 
                TOGGLE COLOR
            </button>
            <button id="random-color"> 
                RANDOM COLOR
            </button>
            <button id="convert-to-line">
                CONVERT TO INLINE
            </button>
        </div>
        <div class="main">
            <div class="startups-container">

            </div>

        </div>
        <div class="footer">

        </div>

    </div>
</body>

</html>

<style>
    .root-container {
        position: relative;
    }

    .root-container .header {
        position: relative;
    }

    .root-container .main {
        position: relative;
    }

    .root-container .footer {
        position: relative;
    }

    .startups-container {
        background-color: gray;
    }

    .red {
        background-image: red;
    }

    .blue {
        background-image: blue;
    }

    .gold {
        background-image: gold;
    }
</style>

<script>
    var colors = ['red', 'blue', 'gold'];
    var chicagoStartupsHTML = [];
    var chicagoStartups = [
        '  Interior   Define  ',
        'Classkick',
        'teaBOT  .$',
        'Pritzker Group Venture Capital',
        'Teln!yx !!',
        'ShipBob ~~$$$',
        'Hologram',
        'Tovala    ',
        '    MANOR',
        'ShuttleCloud 999987',
        'gtrot @@@@@',
        'DealsGoRound ****',
        ' Groovebug',
        'Stage$$$Bloc',
        'Shiftgig',
        'ParkWhiz'
    ];
    $(document).ready(function () {
        $.each(chicagoStartups, function (index, startupName) {
            chicagoStartupsHTML.push('<div>' + startupName + '</div>');
        });
        $(".startups-container").html(chicagoStartupsHTML.join(""));
    });

    //HOMEWORK 1 PROBLEMS START
    // 1.CREATE A FUNCTION THAT REVERSES THE LIST OF STARTUPS ON CLICK OF THE REVERSE BUTTON

    $(document).ready(function (){
	$('#reverse').click(function() {
		
chicagoStartups.reverse();
var list = chicagoStartups;
var newHTML= [];

$.each(list, function (index, elements) {

 newHTML.push('<div>' + elements + '</div>');

});
        $(".startups-container").html(newHTML.join(""));


});

});



    // 2.CREATE A FUNCTION THAT REMOVES ALL SYMBOLS AND NUMBERS FROM COMPANY NAMES ON CLICK OF REMOVE SYMBOLS & NUMBERS BUTTON 
    //   Stage$$$Bloc => StageBloc

 $(document).ready(function (){
	$('#remove-symbols-numbers').click(function() {


chicagoStartups= chicagoStartups.toString();

var letterOnlyList = chicagoStartups.replace(/[^A-Za-z,' ']+/g, '');

var arrList = [letterOnlyList];

var newHTML2= [];

$.each(arrList, function (index, elements) {

 newHTML2.push('<div>' + elements + '</div>');

});
       $(".startups-container").html(newHTML2.join(""));

    //   $(".startups-container").html(letterOnlyList);

});

});



    // 3.CREATE A FUNCTION THAT SORTS STARTUPS IN ALPHABETICAL ORDER ON CLICK OF THE SORT BUTTON
   $(document).ready(function (){
	$('#sort-alphabetically').click(function() {
		
var list3 = chicagoStartups;
var newHTML3= [];

$.each(list3, function (index, elements) {

 newHTML3.push('<div>' + elements + '</div>');
newHTML3.sort();

});
        $(".startups-container").html(newHTML3.join(""));


});

});


    // 4.CREATE A FUNCTION THAT TOGGLES THE BACKGROUND COLOR UPON CLICK OF THE TOGGLE COLOR BUTTON

$(document).ready(function (){
	$('#toggle-color').click(function() {


$('.startups-container').css("background-color","red");

});

});


    // 5.CREATE A FUNCTION THAT RANDOMLY SELECTS A COLOR CLASS AND APPLIES IT TO EACH COMPANY NAME WHEN THE COLOR BUTTON IS CLICKED



    // 6.CREATE A FUNCTION THAT DISPLAYS STARTS AS INLINE ELEMENTS ON CLICK OF CONVERT TO INLINE BUTTON


$(document).ready(function (){
	$('#convert-to-line').click(function() {


chicagoStartups= chicagoStartups.toString();

var letterOnlyList = chicagoStartups.replace(/[^A-Za-z,' ']+/g, '');


 $(".startups-container").html(letterOnlyList);

});

});





    //HOMEWORK 1 PROBLEMS END

</script>
