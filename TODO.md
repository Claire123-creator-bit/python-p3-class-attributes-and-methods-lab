# Song Class Implementation Plan

## Steps to Complete:

1. [ ] Implement Song class with instance attributes: name, artist, genre
2. [ ] Add class attributes:
   - count (total song instances)
   - genres (list of unique genres)
   - artists (list of unique artists)
   - genre_count (dictionary counting songs per genre)
   - artist_count (dictionary counting songs per artist)

3. [ ] Implement __init__ method that:
   - Initializes instance attributes
   - Calls class methods to update class attributes

4. [ ] Implement class methods:
   - add_song_to_count() - increments count
   - add_to_genres() - adds genre to genres list (unique)
   - add_to_artists() - adds artist to artists list (unique)
   - add_to_genre_count() - updates genre_count dictionary
   - add_to_artist_count() - updates artist_count dictionary

5. [ ] Test the implementation
