# Project 1 - Flixter

**Flixter** is a movies app using the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

Time spent: **4** hours spent in total

## User Stories

The following **required** functionality is complete:

- [X] User can view a list of movies currently playing in theaters from The Movie Database.
- [X] Poster images are loaded using the UIImageView category in the AFNetworking library.
- [X] User sees a loading state while waiting for the movies API.
- [X] User can pull to refresh the movie list.

The following **optional** features are implemented:

- [X] User sees an error message when there's a networking error.
- [ ] Movies are displayed using a CollectionView instead of a TableView.
- [X] User can search for a movie.
- [ ] All images fade in as they are loading.
- [ ] Customize the UI.

The following **additional** features are implemented:

- [ ] List anything else that you can get done to improve the app functionality!

Please list two areas of the assignment you'd like to **discuss further with your peers** during the next class (examples include better ways to implement something, how to extend your app in certain ways, etc):

1. I'd like to know if there are better ways to implement the search bar so that it doesn't have to just be at the top in the navigation bar.
2. I'd like to learn how to extend my app to possibly include the videos for the trailers of the selected movies.

## Video Walkthrough 

Here's a walkthrough of implemented user stories:

<img src='/use-case-playthrough.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Notes

I definitely was challenged to add the search bar because the code provided through CodePath wasn't exactly up to date. Additionally, I struggled a little to get the network error to appear how I wanted it to since I also had to manually update some of the code for those methods as well.

## License

    Copyright 2017 Diana Chen

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
