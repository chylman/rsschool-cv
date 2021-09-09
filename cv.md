# CV - Ilya Afanasev

## Contact information

* Adress: Russia, Saint-Petersburg
* E-mail: chylmanprosto@gmail.com
* Whatsapp: +79880885988
* Telegram: @chylman
* GitHub: [Ilya Afanasev](https://github.com/chylman) 

## About me

I am a junior frontend developer. I have been developing for about a year. My Characteristic qualities: purposefulness, involvement, self-development. I try to find mutual understanding with the employer in order to be useful to each other.

## Skills

* HTML
* CSS (Framework Bootstrap, Preprocessor SCSS, BEM methodology).
* JavaScript (Fundamentals,Functional Programming, OOP, Asynchronous JavaScript, ES6+,DOM),JSON.
* Version control: Git (remote service GitHub).
* Module Bundlers: Gulp, Webpack.
* Windows OS, Linux(Ubuntu)
* Figma(for web development), Photoshop

## Education

Volgograd Social and Pedagogical University (2014), specialty: mathematics-computer science

## Experience

HTML Academy course Frontend Developer (2021)

Projects(HTML, JS, CSS):
* [Booking](https://github.com/chylman/1517165-keksobooking-22)
* [Jewellery](https://github.com/chylman/jewellery)
* [Bicycles](https://github.com/chylman/bicycles)
* [Pink](https://github.com/chylman/1517165-pink-21)
* [SmartDevice](https://github.com/chylman/smart-device)

## Code Examples

```javascript

const checkStatus = (response) => {
  if (response.ok) {
    return response;
  }

  throw new Error();
}

const getData = (onSuccess) => {
  fetch(GET_DATA_URL)
    .then(checkStatus)
    .then((response) => response.json())
    .then((ads) => {
      onSuccess(ads);
    })
    .catch(displayGetDataErrorMessage);

}

const sendData = (onSuccess, onFail, body) => {

  fetch(POST_DATA_URL,
    {
      method: 'POST',
      body,
    },
  )
    .then(checkStatus)
    .then(() => {
      onSuccess();
      adForm.reset();
      filterForm.reset();
      resetMainMarker();
      resetIconAdMap();
      onSelectAdTypeChange();
      removePreviewImage();
    })
    .catch(() => {
      onFail();
    })
}

```

## English

Pre-Intermediate (A2+)

I am learn English every day (youtube, duolingo).