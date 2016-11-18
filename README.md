# Rednote Coding Challenge

Here's some background information on how we currently generate SongStickers.

	We use FFMPEG and ImageMagick. The process of generating a video clip has two steps. 

	1. In the first steps, we use ImageMagick to render 3 static images that we use as layers in the video:
	• album cover or user image as a background
	• lyric text, (may include artist name and song title)
	• overlay with the rednote logo or rednote.com (watermark)

	2. In the second step, we use FFMPEG to combine the image layers together and convert them into the video, add audio track and the equalizer animation.

	We use the tools in other parts of the project too… ImageMagick for any image manipulation (resizing, etc) and FFMPEG for cutting songs into clips.

	We can use various fonts, colors, sizes, transparency, etc… 

	The reason we are rendering on the cloud is that we host the song clips (mp3) on AWS.

Please organize, design, and document your code that will be reviewed by our engineers for iOS. 

As we discussed, we'd like to create an animated lyric video solution that incorporates the customization tools currently in Rednote iOS.

We're looking to explore animated filters (think Snapchat geofilters but with movement), responsive lyrics (karaoke style), etc. We can apply various fonts, colors, sizes, layouts, and filters.

Feel free to make any changes/recommendations to the UI/UX, and any additional features you might find valuable for the user experience.

####

# Requirements:

Implement a function that allows the user the ability to add dynamic animated lyric videos onto a photo and/or video.

Please use the following information to integrate into the videos.

Lyric string:
It's something unpredictable But in the end it's right I hope you had the time of your life
Green Day - Good Riddance

Don't wanna be an American idiot One nation controlled by the media
Green Day - American Idiot

I walk this empty street on the boulevard of broken dreams
Green Day - Boulevard Of Broken Dreams

Audio clips - I've attached the audio clips for your reference.

####

We believe there is no one-size-fits-all solution/tech. Please feel free to mention in your comments on how your recommendations will improve the application's performance, functionality, and overall usability.

Please let me know if you have any additional questions. As I mentioned, please take your time and I look forward to chatting!




