sassanimation
======

A custom sass animation library based on http://mikefowler.me/companimation/.

This version will include the ability to run without compass so there's no conflict with the latest alpha versions, and the ability to be used through libsass.

Clean-up of original animation code, and hundreds of animations will be available to use with a simple syntax.

The library will be included by default in the upcoming woocss.com framework.

-------------------------------------------

Call the animation settings via include, then apply to your html i.e 

@include fadeindown;
@include fadeinup;
@include spin;

test-animation {
  @include animation('fadeindown 1s', 'spin 1s 1.1s ease', 'fadeinup 1s 2.1s forwards');
}



