Data for Audio and Video
=========
* Not a lot of people incorporate data into other forms of journalism


## Data for Radio
* lots of mapping and analysis, but the end product is always a person or story
* There are other ways of bringing data into audio journalism
  * Data = Sound! For example, gravitational waves, you can hear the gravity waves, and you can incorporate that into reporting
  * Information can be heard
* data relay is important, think about how you can hear what is in the environment that is representative of the data you analyzed
* data can also be a character in the story, can let people hear change

## Data as Audio: Sonifying earthquakes
Mike Corey, CIR
* CIR became a radioshow, the data folks had to think of how to make data felt on the radio
  * they brainstormed how they could use earthquake data to tell a compelling audio story, had freedom to really experiment
* Sonifying the earthquake data turned out more interesting than the print story
  * earthquakes started happening more and more frequently, and they had different magnitudes, an occurrence and a size, so you can make each earthquake a note
    * ran earthquake data through a synthesizer, each note in the song is an earthquake and the magnitude is the note
    * allows you to hear just how the frequency of earthquakes
    * a great way of conveying there used to be no earthquakes to a great number
* Lots of libraries to create noise from data
* Midi - musical instrument digital interface
  * audiofiles are waveforms, midi is a vector
  * a song in midi is a list of notes, you tell the program at what beat to play which note for how many beats
    * Hard part is mapping midi notes to time
    * treated musical notes as a scale and the magnitude as a scale, mapped data values to scale values
* This is a very direct note to data thing, but the DataDrivenDJ does a lot of playful links between different kinds of data and sound
  * example, wrote a song that maps income inequality to subway stops, has two variables, subway stop and income inequality, the song changes to have more instruments based on how rich the stop is

## Data as Video
Kavya Sukumar, Vox Product
* video has been around for a long time, is already on all devices and sites
* has a ton of cms support, and its fun to make
* what makes good video
  * basically a TLDR for longform, use it to show and share the shortform version of your longer article or investigation
    * animation allows you to visualize and put under the audio
* very popular to use video as a concept explainer
  * Vox used an explainer video to explain the math and logic behind leap-day, allows both data vis and a person's voice explaining what everything is
* video as promotions for stories
  * promote your stories!! make previews for your story. Introduce the problem or story that you want to spend a lot of time telling, you can use the video to drive interest
    * social media promotion of a multi-part series
* Video can also include overlays, videos of people drawing and explaining, both high tech and low tech
* CIR used stop-motion to visualize pesticide and their impact on strawberries
  * made a tough subject engaging and visually appealing through a unique way of presenting
* Vox has used animated graphics with an audio-explainer overlaid, to explain what the movements of the lines mean
  * autotune - a chart animator that will soon be released
  * chitram - knight-funded chart animator

## Data From Video
Nancy Watzman, Political TV Ad Archive
* how do we get data from videos and then use that to do reporting
* Political TV Ad Archive has petabytes of TV news archives, captures news broadcasts to 2009 searchable by closed captioning
  * idea is to build off of other projects tracking spending on political ads, captured political ads in Philly and from that reported on who was spending to influence the election
* Tracking 8 key primary states, generates structured data from the ads, such as who it is in support of, the media market it is airing in
  * partners with national fact-checking groups and money-tracking groups to show how the video and the payer in within the greater spectrum of the election
* they have a tool that analyzes the audio from the videos as well
  * you can search videos by subject
* See which ads are airing the most, which programs are they aired on, what are their subjects, is it positive or negative, who paid for it, how much they paid
* You can download so much information off the site, they exist to get the data out into the world, you can use a lot of visual and audio data to tell stories about the ads
* The transcripts of all the ads will be soon be available to download as a csv
* They built an open-source tool to pipe the ads into and then analyze the audio to create the transcripts

### Questions
* Q: How do you decide what to do with the data in terms of transforming it to other mediums
  * A: it's an editorial decision, requires a bit of thinking and experimenting and creativity. What would we have said about the data on the radio, and how could we say it differently?
* Q: On Political TV, how did you code the subjects of the video?
  * A: It was hand-coded by archivists at the Internet Archive
* Q: How do you explain multi-dimensional data with audio, how much do you need to explain about it?
  * A: with audio you can have people ask about the sound/sonification, which allows explainers and the song to be overlaid
  * the radio-host can explain the dimensions of sonification with the person who made it while listening, creativity in presentation too
* Q: How do you convince the powers that be that these projects are worthwhile
  * A: it depends on the editor, make a high quality product and the editors should be cool with it. Experimentation needs support though, if you believe it can work, and you can get a demo working. CIR fought hard to keep the song into the earthquake story
  * "demos not memos", show that it works
  * Also you have to try new things to not be unrelentingly depressing
