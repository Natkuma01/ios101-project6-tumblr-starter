# Project 6 - Tumblr Detail

Submitted by: Natalie Chan

The Tumblr Detail is an iOS application allows users to browse and view posts from a Tumblr blog. It displays a list of posts in a table view, showing a summary and an accompanying image for each. Tapping on a post navigates the user to a detail screen where they can see the full caption and a larger version of the image.

Time spent: 5 hours spent in total

## Required Features

The following **required** functionality is completed:

- ✅ Setup navigation to the Detail Screen
- ✅ Created the Detail View UI
- ✅ Add the ability to pass data to the Detail View Controller
- ✅ Made personal finishing touches to the UI


## Video Walkthrough

<div>
    <a href="https://www.loom.com/share/09779d8ded094132bdae9d6a4fb7a8cc">
      <p>Loom Message - 22 July 2025 - Watch Video</p>
    </a>
    <a href="https://www.loom.com/share/09779d8ded094132bdae9d6a4fb7a8cc">
      <img style="max-width:300px;" src="https://cdn.loom.com/sessions/thumbnails/09779d8ded094132bdae9d6a4fb7a8cc-96dc1614a79c3296-full-play.gif">
    </a>
  </div>

## Notes

The biggest challenges but also a big learning moment are the navigation controllers and storyboard segues. I didn’t fully understand the difference between pushing a view controller using a navigation stack versus presenting it modally. This became obvious when my detail view would slide up modally and not show the standard back button. I eventually realized I had to remove the segue from the table cell and instead perform the segue manually in code. I also learned how to embed my main view controller in a UINavigationController, and how to set the navigation hierarchy correctly so that the "Back" button would show up and function as expected.

## License

    Copyright [2025] [Shimin Chan]

    Licensed under the Apache License, Version 2.0 (the "License");
    you may not use this file except in compliance with the License.
    You may obtain a copy of the License at

        http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing, software
    distributed under the License is distributed on an "AS IS" BASIS,
    WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
    See the License for the specific language governing permissions and
    limitations under the License.
