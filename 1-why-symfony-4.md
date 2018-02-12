# Why Symfony 4

## Welcome

Hi all,

Welcome to first video of Symfony 4 series.

## Lets start with short intro about me & and PHP Reboot

Well, I'm Kapil Sharma, VP-Technology at D.J. Alexander India and community leader at PHP Reboot - PHP developers community in Pune, India.

At PHPReboot, we organize several PHP and related technology meetup in pune. By name, it is PHP Reboot but actually it should be Tech reboot as we discuss things applicable to all languages like improving code quality, refactoring, etc and related technologies like Angular, Node, Mongo DB etc.

## ~~Availability of this course~~

Give me a min more to discuss about availability of this course. If you are viewing it in youtube, please check the description below for other videos in the series. Alternatively, you can also check the videos on Kapilsharma.info or phpreboot.com, where will be listed serially.

If you prefer written version, you can find the link to github repository, which have written version of this tutorial.

## ~~This video~~

Coming to this video, in this section or first video, we are trying to answer following questions:

- Why PHP (vs other languages)
- Why use a framework (vs CMS)?
- Why Symfony 4?
- What is the advantages and disadvantages of symfony 4?
- Under what circumstances, I do not recommend using Symfony?

### First question - Why PHP?

Well, programming language doesn't really matter. Although I have little more and recent experience with PHP but I never introduce me as PHP developer. I'm developer, not php or python or JS or java developer.

I could see many questions on internet about lanmguages, if PHP is good enough or what language should I select.

In short, I'd suggest choose any language if it meet two conditions:

1. you are confortable with and
1. if it can get your job done very well and with proper quality and future consideration.

And these are my reasons to select PHP for most projects. Although I worked with Java, Dot net, Python, Node JS or JS in particular, I'm most confortable in PHP. Also, PHP is one of the top languages with huge community and can do the jobs very well.

If you want to read further on that, go to one of my articles on [linkedin](https://www.linkedin.com/pulse/20141010201130-58631725-career-1-0-selecting-first-programming-language/?lipi=urn%3Ali%3Apage%3Ad_flagship3_profile_view_base_post_details%3BJyH5oGXbTOmdQLzlCaCY0w%3D%3D). Article link is available in description. It is an old article but still perfectly correct.

### Second question - Framework vs CMS

Not only in PHP, but across nearly all languages, there are many CMS. They make your task really easy to make a quick website. Also, you may update them for custom plugins, components or whatever they call it to make your specific requirements.

Still, I generally do not recommend CMS in most cases. There are few cases, where your application is content rich, which needs to be updated daily by non-technical purpose, CMS are good there.

I'd suggest to use CMS if it needs to be set once, with very minimal custom code and later to be maintained by non-technical persons. However, msot projects are not of that category.

People, mainly CMS developers suggest CMS can do anything. Yes it can but not in efficient manner. Remember, CMS is very generic case. If you have specific requirements, generic solution will work for you but not at its best.

It put another question

### Aren't frameworks generic?

They are. Infect once [someone ask Rusmus](https://www.youtube.com/watch?v=DuB6UjEsY_Y) - The creator of PHP, What he thinks about frameworks and he said

> `They all suck`

That is an interesting video, I'd provided link in description. He further explains:

- All need framework
- but not general purpose framework.

So he probably gave same argument like the one I gave for CMS. A general purpose framework can get the job done but it also include so many thing, that we never need in our project but still pay price in terms of CPU cycle and remember, CPU on server is very costly.

Till last year, I was suggesting Laravel for small and mid-level projects. Laravel is another PHP framework but with much smaller footprint then Symfony 2 and 3. You can see my that video titled [Selecting PHP Framework for your next project (2017)](https://www.youtube.com/watch?v=U7rR3ZobH4k) through link given in description but now even I feel it is outdated with Symfony 4.

### Then, Why Symfony 4?

How symfony 4 changed all that. Well, symfony 4 is very minimal framework, so minimal, that it have less then 20 files when installed (except vendor). It is much lower then even micro frameworks. From there, we add things which we need to solve our specific problem.