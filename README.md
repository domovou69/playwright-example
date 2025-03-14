# playwright-example

- To run tests use commands:
- npm i
- npm run test

## Suite 1: Wallpapers: Search, Filtering - Guest User

### Step 1: Search wallpapers by keywords

TC-01: Single and multiple words search (e.g. “sun” "mountains river") --- relevant results are displayed.
TC-02: Auto load images on scroll down. --- previous wallpapers load should be preserved, relevant results should be added

### Step 2: Filtering wallpapers by category, color, tags, price and sort by

TC-03: Apply filter by category ("nature") --- validate free and premium images
TC-04: Filtering by color ("pink") --- validate free and premium images
TC-05: Filter by tags ("black") --- validate free and premium images
TC-06: Filter by price (free vs premium) --- only relevant images are displayed.
TC-07: Filter by sort by --- only relevant images are displayed.
TC-08: Apply multiple filters at once > reset filters --- all filters removed

## Suite 2: Wallpapers: Downloading and Purchase - Guest User

### Step 3: Checking unique wallpaper page

TC-09: Selecting any wallpaper should redirect to it's unique URL page --- validate unique wallpaper page

### Step 4: Downloading images

TC-10: Attempting to download a premium image should offer to purchase the image is displayed.
TC-11: Attempting to download a free image should show AD for 15 sec, then start downloading --- check image downloaded and not corrupted
