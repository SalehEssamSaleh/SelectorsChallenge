# SelectorsChallenge

This Frontend Challenge from Twitter
- CSS Selector Challenge.
- The Core of the Challenge is to use nth-child() selectors.

## Languages:
- HTML
- CSS

## Notes:
- Like always I walk around the core of the Challenge, I didn't use " nth-child() instead I used nth-of-type() selector ".
- The code is not clean enough.
- I flipped the sections " I but the Buttons first then I added the circles ==> Just to be able to use Cascading, for example :

  - when I Press Button No.1 => select Div No.1 ==> The Code Version ==> #first-child:focus ~ div:first-of-type

- I know there is a way to flip sections to look like the Challenge Example: "https://twitter.com/b_wffa/status/1741525526303416448"

  - But maybe in the future when I back to coding more using CSS and study the " Display features " I will back to this repo and edit the code to look Exactly Like the Challenge Example.
 
## What I learned from this Challenge:
- How to use " nth-child & nth-of-type " Selectors
- The CSS :focus  Selector is used to select and style the focused button " Pressed Button " or link. 
- How to call another Element in CSS using " ~ " for example:

  - I want to make an action on another element when I press a specific button =>
    - for example, the button has id = "btn-one", and the element I want to make an action on is some "div"
      - so to do all of this using CSS, all I need to use is this Magical tiny symbol ~
      - so in CSS it will look like this =>  #btn-one:focus  ~ div:nth-child() { };
***
After all the Challenge looked easy at the beginning but once I started Coding the real face of the Challenge appeared,
but I enjoyed Practicing this Challenge and I gained new Information.
