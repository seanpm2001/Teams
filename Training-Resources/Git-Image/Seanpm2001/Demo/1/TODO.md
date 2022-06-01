
***

# Git-image file naming training course

This basic training course will teach you the basics of my Git-image file organization systemn,

## Step 1: sort the files

The files have to be sorted. Let's start with GNOME System Monitor screenshots. There are 2 mega categories for this application: GNOME System Monitor and battery progress.

Battery progress shots will have a white box in the upper right corner of the screen. Any files you see with a white box like this should be categorized as a battery image directory, and should be placed in the battery directory, under the day it was from.

The other sub-categories for GNOME System Monitor include:

- [ ] End of day (partitions)
- [ ] End of day (Monitor)

Only the very last 2 files of the day contain this category, and should be named as such. The screenshot that shows partitions/drives is the complicated looking one. The screenshot that shows the monitor is everything but that.

## Step 2: rename the files

For GNOME System Monitor instructions, see step 1

### Step 2.1 - Daily Desktop Screenshots

<abbr title="Daily Desktop Screenshots">DDS</abbr> is a 1 image per day category. it should be named the same as the previous entry, with the number increased by 1 and the date adjusted corresponding to the date the shot was taken.

It should look like this:

- [ ] `DailyDesktopScreenshot1501_2022May30th_1080p.png`

### Step 2.2 - Khan Academy

<abbr title="Khan Academy">KA</abbr> is also a 1 image per day category. it should be named the same as the previous entry, with the number increased by 1 and the date adjusted corresponding to the date the shot was taken.

It should look like this:

- [ ] `KhanAcademy_Day1823_MissedDaysEqualsOne_2022May30th_1080p.png`

The line `MissedDaysEqualOne` was added when I missed a consecutive day back in 2021.

### Step 2.3 - GitHub Commit Milestones

Commit count milestones are a category of GitHub screenshots. They are the first in the order. Milestones are usually multiples of 100, but sometimes, special occassions are marked with Palindromes. Sometimes, Sean misses the multiple of 100 by 1 to 10 as well.

For an example set on 2022 January 1st:

There is a milestone for 100 commits. There is a light mode and a dark mode variant. The files would be named as so:

- [ ] `GitHub_EndofDay_2022January1st_100Commits_LightMode_1080p.png`
- [ ] `GitHub_EndofDay_2022January1st_100Commits_DarkMode_1080p.png`

Each field is separated by an `_` underscore.

If the multiple of 100 is missed, it can be written like so:

- [ ] `GitHub_2022January1st_101Commits_1CommitOff_LightMode_1080p.png`
- [ ] `GitHub_2022January1st_101Commits_1CommitOff_DarkMode_1080p.png`

For palindromes, the palidrome must be stated. Take the following example:

- [ ] `GitHub_Palindrome_2022January1st_101Commits_LightMode_1080p.png`
- [ ] `GitHub_Palindrome_2022January1st_101Commits_DarkMode_1080p.png`

This usually isn't the palindrome type to be celebrated. More common ones include:

- [ ] 1001
- [ ] 2002
- [ ] 2222
- [ ] 11011
- [ ] etc.

Key fields to note are:

- [ ] `GitHub` (1)
- [ ] `EndofDay` (2)
- [ ] `Palindrome` (2.1)
- [ ] `Date (yyyy/mm/dd)` (3)
- [ ] `Commit count` (4)
- [ ] `Commits off` (4.1)
- [ ] `Light/Dark Mode` (5)
- [ ] `Resolution (1080p, 1440p, 2160p)` (6)

### Step 2.4 - GitHub End of day (profile)

There are 6 categories for GitHub end of day on the profile page. There originally used to be only 1 (the commit count one, by the current year)

The first one in the order is for the profile page. It can look like this:

- [ ] `GitHub_445Followers_3.1KFollowing_NaNStars_2022May30th_LightMode_1080p.png`
- [ ] `GitHub_445Followers_3.1KFollowing_NaNStars_2022May30th_DarkMode_1080p.png`

Key fields to note are:

- [ ] `GitHub` (1)
- [ ] `X Followers` (2)
- [ ] `X Following` (3)
- [ ] `X Stars` (4)
- [ ] `Date (yyyy/mm/dd)` (5)
- [ ] `Light/Dark Mode` (6)
- [ ] `Resolution (1080p, 1440p, 2160p)` (7)

After a GitHub update in early 2022, the star count was replaced with `NaN` as the exact number can no longer be easily found.

We are now 1/3 of the way through this process. We will now go for the GitHub end of day for the past year category.

The second one in the order is for GitHub commits by the last 365/366 days. It can look like this:

- [ ] `GitHub_YearTotal_EndofDay_78498Commits_2022May30th_LightMode_1080p.png`
- [ ] `GitHub_YearTotal_EndofDay_78498Commits_2022May30th_DarkMode_1080p.png`

Key fields to note are:

- [ ] `GitHub` (1)
- [ ] `YearTotal` (2)
- [ ] `End of Day` (3)
- [ ] `X Commits` (4)
- [ ] `Date (yyyy/mm/dd)` (5)
- [ ] `Light/Dark Mode` (6)
- [ ] `Resolution (1080p, 1440p, 2160p)` (7)

Now for the final step. The third one in the order is for GitHub commits in the current year. It can look like this:

- [ ] `GitHub_EndofDay_31664Commits_2022May30th_LightMode_1080p.png`
- [ ] `GitHub_EndofDay_31664Commits_2022May30th_DarkMode_1080p.png`

Key fields to note are:

- [ ] `GitHub` (1)
- [ ] `End of Day` (2)
- [ ] `X Commits` (3)
- [ ] `Date (yyyy/mm/dd)` (4)
- [ ] `Light/Dark Mode` (5)
- [ ] `Resolution (1080p, 1440p, 2160p)` (6)

These screenshots are the first in the process of end of day screenshots. In the naming order, they come right after the commit count milestones.

### Step 2.5 - GitHub End of day (individual repositories)

This is the longest part, as I work on between 6 and 25 repositories per day. This equates to 12 to 50 screenshots for this category.

I will only reference 2, as the process is the same for all of them, and there are only 2 in this demo at the moment.

- [ ] `SeansLifeArchive_Images_TinyTowerRepo_EndofDay_2022May30th_2692Commits_LightMode_1080p.png`
- [ ] `SeansLifeArchive_Images_TinyTowerRepo_EndofDay_2022May30th_2692Commits_DarkMode_1080p.png`
- [ ] `SeansLifeArchive_Images_GNOME_System_MonitorRepo_EndofDay_2022May30th_1431Commits_LightMode_1080p.png`
- [ ] `SeansLifeArchive_Images_GNOME_System_MonitorRepo_EndofDay_2022May30th_1431Commits_DarkMode_1080p.png`

The order goes like this:

- [ ] `Repository name, followed by the word "Repo"` (1)
- [ ] `End of Day` (2)
- [ ] `Date (yyyy/mm/dd)` (3)
- [ ] `X Commits` (4)
- [ ] `Light/Dark Mode` (5)
- [ ] `Resolution (1080p, 1440p, 2160p)` (6)

That is the end of this demo.

## Notes

### Light Mode & Dark Mode

Pictures are available in both light mode and dark mode ever since GitHub added light mode. This is done, as light mode is preferred by some people, and dark mode is preferred by other people

Ever since the GitHub colorblind update, I switched to the colorblind option. It later got renamed to tritanopia, which is what I still use.

## Automation

I am hoping to automate this process in the future.

***

## File info

**File type:** `Markdown document (*.md *.mkd *.mdown *.markdown)`

**File version:** `2 (2022 Wednesday, June 1st at 1:51 pm PST)`

**Line count (including blank lines and compiler line):** `186`

**Current article languuage:** `English (USA)`

***

