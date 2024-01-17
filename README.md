# securities-raml-fragment
<a name="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <!-- <a href="https://github.com/jonathanfiss/securities-raml-fragment">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a> -->

  <h3 align="center">Securities Fragment RAML</h3>

  <p align="center">A template with reusable fragments to boost your projects!</p> 
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

The **Securities RAML Fragment** project aims to streamline the development of RAML (RESTful API Modeling Language) specifications by adhering to predefined standards for security schemas. It provides a set of reusable fragments focused on security, enabling the creation of consistent and standardized RAML specifications for APIs.

## Project Contents

The project encompasses 7 distinct security schemas, each serving a specific purpose in securing your APIs:

1. **clientEnforcement**: Standard client enforcement security schema.

2. **basicAuthentication**: Basic authentication security schema.

3. **digestAuthentication**: Digest authentication security schema.

4. **oAuth1.0**: OAuth 1.0 authentication security schema.

5. **oAuth2.0**: OAuth 2.0 authentication security schema.

6. **passThrough**: Pass-through security schema.

7. **anotherAuthentication**: Custom security schema tailored for specific requirements.

The `anotherAuthentication` security schema stands out as a customized solution, while the others are predefined by RAML. This diversity allows you to choose and implement the most suitable security measures for your API.

The **Securities RAML Fragment** project facilitates the integration of various security schemas into your RAML specifications, promoting a secure and standardized approach to API development.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage Instructions

1. Create a new RAML Fragment project in Design Centre named: "Securities RAML Fragments"
2. Add all the contents of this repository into a ZIP excluding the license and readme.md file.
3. Go to your Design Centre Project and choose "Import", then select the ZIP.
4. Ensure you set the root RAML as the one which has been imported.
5. Publish this asset to Exchange.
7. This asset can now be imported into any new API Specification Design Centre project.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Used as the basis for creating this template.

* [reusable-raml-fragments]([https://medium.com/@shiv.jalli_26300/getting-started-with-raml-1-0-406377f8c1ab](https://github.com/mulesoft-catalyst/reusable-raml-fragments))
* [3 types of API fragments design strategies](https://blogs.mulesoft.com/api-integration/patterns/api-fragments-design-strategies/)
* [RAML Version 1.0: RESTful API Modeling Language](https://github.com/raml-org/raml-spec/blob/master/versions/raml-10/raml-10.md/#resource-types-and-traits)


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/jonathanfiss/securities-raml-fragment.svg?style=for-the-badge
[contributors-url]: https://github.com/jonathanfiss/securities-raml-fragment/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/jonathanfiss/securities-raml-fragment.svg?style=for-the-badge
[forks-url]: https://github.com/jonathanfiss/securities-raml-fragment/network/members
[stars-shield]: https://img.shields.io/github/stars/jonathanfiss/securities-raml-fragment.svg?style=for-the-badge
[stars-url]: https://github.com/jonathanfiss/securities-raml-fragment/stargazers
[issues-shield]: https://img.shields.io/github/issues/jonathanfiss/securities-raml-fragment.svg?style=for-the-badge
[issues-url]: https://github.com/jonathanfiss/securities-raml-fragment/issues
[license-shield]: https://img.shields.io/github/license/jonathanfiss/securities-raml-fragment.svg?style=for-the-badge
[license-url]: https://github.com/jonathanfiss/securities-raml-fragment/blob/master/LICENSE.txt

