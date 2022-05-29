<div align="center" id="top"> 
  <img src="https://github.com/hediet/vscode-drawio/raw/HEAD/docs/drawio-png.gif" alt="DrawIO" />

&#xa0;

  <!-- <a href="https://modelagem.netlify.app">Demo</a> -->
</div>

<h1 align="center">Modeling</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/jocile/Modeling?color=56BEB8">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/jocile/Modeling?color=56BEB8">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/jocile/Modeling?color=56BEB8">

  <img alt="License" src="https://img.shields.io/github/license/jocile/Modeling?color=56BEB8">

  <!-- <img alt="Github issues" src="https://img.shields.io/github/issues/jocile/modelagem?color=56BEB8" /> -->

  <!-- <img alt="Github forks" src="https://img.shields.io/github/forks/jocile/modelagem?color=56BEB8" /> -->

  <!-- <img alt="Github stars" src="https://img.shields.io/github/stars/jocile/modelagem?color=56BEB8" /> -->
</p>

<!-- Status -->

<!-- <h4 align="center">
	🚧  Modelagem 🚀 Under construction...  🚧
</h4>

<hr> -->

<p align="center">
  <a href="#dart-about">About</a> &#xa0; | &#xa0; 
  <a href="#sparkles-features">Features</a> &#xa0; | &#xa0;
  <a href="#rocket-technologies">Technologies</a> &#xa0; | &#xa0;
  <a href="#white_check_mark-requirements">Requirements</a> &#xa0; | &#xa0;
  <a href="#checkered_flag-starting">Starting</a> &#xa0; | &#xa0;
  <a href="#memo-license">License</a> &#xa0; | &#xa0;
  <a href="https://github.com/jocile" target="_blank">Author</a>
</p>

<br>

## :dart: About

The steps presented in this task assume that the application's persistent data design will be implemented using a Relational Database Management System (RDBMS). It is assumed that you are familiar with database concepts, including normalization and denormalization, as well as database terminology, as covered in references such as ERD Modeling.

The steps of this task also refer to the UML (Unified Modeling Language) language profile for database modeling, and contains an overview of the process for modeling and designing relational databases using UML. For additional information about the relationship between relational data models and object models, see Concept: Relational Databases and Object Orientation.

The Entity and Relationship Modeling Exercises from [DevSuperior](https://devsuperior.com.br/) course.

## :sparkles: Features

:heavy_check_mark: Entity relationship diagrams;\
:heavy_check_mark: Class diagrams;\
:heavy_check_mark: Object diagrams;

## :rocket: Technologies

The following tools were used in this project:

- [Diagrams.net](https://app.diagrams.net/)
- [VSCode IDE](https://code.visualstudio.com/docs/editor/vscode-web)
- [Draw.io Integration](https://marketplace.visualstudio.com/items?itemName=hediet.vscode-drawio)

## :white_check_mark: Requirements

To get started :checkered_flag: Modeling can be done online in the browser or using the IDE with the extension Draw.io.

## :checkered_flag: Starting

```
# Modeling
Access https://app.diagrams.net/
```

## :checkered_flag: Diagrams

- :heavy_check_mark: Social network system.

> In this social network, users can follow and be followed by other users. The user's profile must allow the registration of name, email, date of birth, website, gender, phone and profile picture. Users can make text posts on their own "timeline" (timeline) of the social network, and they can also attach photos to the posts. A photo is referenced by the URI of its storage location. The photos can be organized into albums, with each album having a title.

![](SocialNetworkDiagrams/SocialERDiagram.drawio.svg)

## :checkered_flag: More Diagrams

- :heavy_check_mark: [Social Object Diagram](SocialNetworkDiagrams/README.md)

> Minimum instance: 4 users, at least one user with more than one post, at least one album with more than one photo.

- :heavy_check_mark: [Music System Diagrams](MusicDiagrams/README.md)

> Design a System for keeping a record of musical artists and their albums. Each album has several songs, which can be consulted by the system. The system it should also allow searching for artists by name or nationality. The system must also be able to display a report of an artist's albums, which can be sorted by name, year, or duration album total. An album can have the participation of several artists, without distinction. Now the music can have one or more authors and performers (all considered artists).

> Minimum Instance: 2 artists, 3 albums, 4 songs.

- :heavy_check_mark: [Footballs System Diagrams](FootballDiagrams/README.md)

> Design a system to manage the information of championships of football, which take place every year. You want to know the name, date of birth, gender and height of the players of each team, as well as which one is the captain of each team. Each championship match takes place in a stadium, which has a name and address. Each team has its home stadium and, thus, each match has a home team (host) and a visiting team. The system must be able to list the matches already held and not held of a championship. The system must also be able to list the championship table, ordering the teams by classification, which is calculated first by win balance and second by goal difference.

> Minimum instance: 1 championship, 2 matches, 2 teams, 2 players on each team.

## :memo: License

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.

## References

- [StarUML documentation - Entity-Relationship Diagram](https://docs.staruml.io/working-with-additional-diagrams/entity-relationship-diagram)
- [UML - ERD modeling](http://www.uml.org.cn/UMLTools/pdf/ermodeling.pdf)
- [UML Tutorials](https://www.startertutorials.com/uml/relationships.html)

Made with :heart: by <a href="https://github.com/jocile" target="_blank">Jocile</a>

&#xa0;

<a href="#top">Back to top</a>
