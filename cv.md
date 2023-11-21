# Ivan Zh-y

# Contacts

* **Discord:** izy_talk
* **GitHub:** [izy-code](https://github.com/izy-code)

# About Me

I have a background in mechanical engineering and am currently delving into frontend development, aiming to master its intricacies and advance my professional expertise.

# Skills

* HTML
* CSS (BEM methodology, SCSS and Less preprocessors)
* JavaScript
* Git (GitHub experience).
* Gulp
* Java (Core)
* Figma, Photoshop

# Code example

```
const setFullSizeModalHandlers = (pictures) => {
  let currentPictureData;

  pictureContainerNode.addEventListener('click', (evt) => {
    const thumbnailNode = evt.target.closest('a.picture');

    if (thumbnailNode) {
      evt.preventDefault();

      const thumbnailId = +thumbnailNode.dataset.thumbnailId;

      currentPictureData = pictures.find(({ id }) => id === thumbnailId);
      openFullSizeModal(currentPictureData);
    }
  });

  commentLoaderNode.addEventListener('click', () => {
    loadComments(currentPictureData.comments);
  });
};
```
