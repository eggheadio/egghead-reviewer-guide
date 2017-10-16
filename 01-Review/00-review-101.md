# Review 101

Video training content goes stale. egghead.io should be as up to date as possible when it comes to content. Because of the nature of video we need to monitor each lesson on multiple levels.

<hr/>

## Lesson Video

An excellent coding screencast will focus on core concepts and have the ability to remain “evergreen” through minor revisions of the library that it is demonstrating. We need to continue to monitor this to make sure that it is the case.

When differences exist we can take several courses of action:

* update the code sample and use comments in the code to notify the user that it has changed from the video
* Annotate the lesson’s page to tell the student what is wrong with the lesson
* Replace the lesson video/code with an updated version
* mark the lesson as obsolete/deprecated
* record a new version (vs replacement)

## Identify Change(s) in a Framework or Library

JavaScript frameworks are constantly changing and updating. A lot of the time this is not an issue for our lessons. Patch updates to software shouldn't break existing code.

However, when `Major` or `Minor` changes occur in a framework this can cause previous versions of the software to break. 

You need to identify these **Breaking Changes** and keep them in mind when watching the video.

Each framework or library will have a `CHANGELOG.md` that will record the changes of that specific framework. ([link to example](https://github.com/facebook/react/blob/master/CHANGELOG.md)) Usually found on the respective frameworks github page.

Most frameworks use Semantic Versioning ([semver](http://semver.org/)) to keep track of updates. We are mostly interested in `Major` and `Minor`

Under each new version, there will be a **Breaking Changes** section that is where you will see what exactly will break any lesson examples that egghead might have.

New features are also tracked in a frameworks `CHANGELOG.md` and should be noted down for possible lesson ideas in the future.

### Update Lesson Code Sample

This is the most common action taken by the reviewer. The lesson code sample should reflect the current version(s) for the libraries it is demonstrating (libraries are updated often!). The sample code can correct for minor differences in the code demonstrated in the lesson video, noting with comments when this has been done.

### Annotate the lesson page

When there is some significant breaking difference in the lesson video and code sample, we can create a notification to be displayed prominently on the lesson page. This notification comes in the form of an `errata` which is shown below:

![Errata Example](../images/01-title-lessons/00-errata-example.png)

### Replace the lesson video/code

If the lesson still has significant value conceptually, we can re-record the lesson and produce an updated code sample. We want to do this for popular lessons and maintain our SEO.

Make a note of why you think the lesson needs to be re-recorded in the review document.

### Mark as obsolete

Like Annotation above, but **more deadly**! :skull:

### Record a new lesson

Sometimes we will want to record a new lesson that presents the underlying concept with the updated version instead of replacing it in-place