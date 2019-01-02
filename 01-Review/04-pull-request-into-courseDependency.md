# Egghead Course Review Dependencies

This is how we want Pull Requests to look.

![How PR's should look](https://res.cloudinary.com/dg3gyk0gu/image/upload/v1545085962/transcript-images/how-prs-should-look.png)

You'll create a new branch starting with your initials followed by a forward slash ie. 'Lm/'. The rest of the branch name should be the slug of the course that you are adding to the master file. 

If you are adding mutiple courses that are part of a promotion, name the promotion as the branch name. 

In the description, we want to have a title. The title will have two '##' with the title being what you did. Below that you want to add in the course slug/slugs that you are PRing. 

The last think you have to have is a gif. If you forget to add a gif, you will need to redo the PR. ;) 

This is that text should look. 

![code of the preview](https://res.cloudinary.com/dg3gyk0gu/image/upload/v1545085962/transcript-images/code-of-the-preview.png)

Here is an example of what the course dependency should look like.

```js
{
  slug: 'start-using-elm-to-build-web-applications',
  dependencies: {
    elm: '0.17',
  },
  reviews: [
    {
      performedOn: '2018-12-14',
      performedBy: '21147',
      scopeOfReview: 'quick course review',
      notes: [
        {
          type: 'major issue',
          title: 'elm-lang moved to elm',
          details:
            'Since version 0.19 elm-lang/* packages have been moved over to elm/*',
        },
        {
          type: 'major issue',
          title: 'Elm.MODULENAME.fullscreen deprecated',
          details:
            'Elm.MODULENAME.fullscreen has been deprecated in favor of Elm.MODULENAME.init',
        },
      ],
    },
  ],
},
```

Here is a blank template.

```js
{
  slug: '',
  dependencies: {
    react: '',
  },
  reviews: [
    {
      performedOn: '',
      performedBy: '',
      scopeOfReview: '',
      notes: [
        {
          type: '',
          dependency: '',
          lessonsAffected: '',
          title: '',
          details:
        },
      ],
    },
  ],
},
```