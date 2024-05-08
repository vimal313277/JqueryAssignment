## Question: 1

#### What is jQuery?

---

<li> jQuery is a lightweight, "write less, do more", JavaScript library.
<li>The purpose of jQuery is to make it much easier to use
    JavaScript on your website.
    <li>jQuery also simplifies a lot of the complicated things from JavaScript, like AJAX calls and DOM manipulation.

    Example:-
    HTML/DOM manipulation
    CSS manipulation
    HTML event methods
    Effects and animations
    AJAX

---

## Question: 2

#### How to Apply CSS Using JQuery, How to Add Class and Remove Class in Jquery, JQuery Animation?

---

       .add {
            background-color: chartreuse;
            font-size: 50px;
            font-weight: 900;
            transition: 3s;
        }
        .temp {
            background-color: red;
            font-size: 50px;
            font-weight: 900;
            transition: 5s;
        }  -->

         .some {
            background: #98bf21;
            height: 100px;
            width: 100px;
            position: absolute;
        }

</head>

    <button>Click Me</button>
    <div class="some">Some</div>
    <div id="temp">Temp</div>

    <script src="https://code.jquery.com/jquery-3.7.1.min.js"></script>

    <script>
        // $('button').click(() => {
        //     $('.some').css({
        //         'background-color': 'red', 'font-size': '100px'
        //     });
        // });

        // =====================

        // $('button').click(() => {
        //     $('.some').addClass('add')
        // })

        // $('button').click(() => {
        //     $('.some').removeClass('add')
        // })


        // ===========

        // $('button').click(() => {
        //     $('#temp').addClass('temp')
        // })

        // $('button').click(() => {
        //     $('#temp').removeClass('temp')
        // })

        // ===================

         $("button").click(() => {
            $(".some").animate({ left: '250px' });
         });

          // ====================

                 $("button").click(() => {
                 $(".some").fadeIn()
                 });
                 $("button").click(() => {
                 $(".some").fadeOut()
                 });
                 $("button").click(() => {
                 $(".some").slideUp()
                 });
                 $("button").click(() => {
                 $(".some").slideDown()
                 });

    </script>

---
