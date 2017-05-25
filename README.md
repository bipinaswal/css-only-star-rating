# css-only-star-rating
sass mixin for css only star rating without images or icons.

It can be used when ratings are fetched from database and corresponding stars have to be shown on view.

Can be used at product rating's and markings. 

# Usage ::
You just need to pass the following parameters when including the mixin, 
1) 'class' for the html element on which star rating is required.
2) 'font-size' to decide size for star.
3) 'dormant color code' for dormant ratings.
4) 'active color code' for active ratings.

# Usage example ::

Html :-
```html
<pre>
    <span class="star-rating rating-3-5"></span><br><!-- used to show 3.5 star rating -->
</pre>
```

Sass Inclusion :-
@include starRating(star-rating, 18, #ddd, #f34747);

Result :-
This will generate star rating of 3.5 with 
element class as 'star-rating', 
font-size of 18px, 
dormant color '#ddd' and 
active color '#f34747'.

