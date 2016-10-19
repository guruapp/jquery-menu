https://jsfiddle.net/wc8p7k91/
# jquery-menu

// javascript jquery

$(document).ready(function() {
    $( '.dropdown' ).hover(
        function(){
            $(this).children('.sub-menu').slideDown(200);
        },
        function(){
            $(this).children('.sub-menu').slideUp(200);
        }
    );
}); // end ready


<!-- html for menu -->
<nav>
  <ul>
  <li class="dropdown">Menu
  <ul class="sub-menu">
  <li>Second 1</li>
  <li>Second 2</li>
  <li>Second 3</li>
  <li class="dropdown">Second 4
  <ul class="sub-menu">
   <li> Inner</li>
  </ul>
  </li>
  </ul>
  </li>
  
  </ul>
</nav>
