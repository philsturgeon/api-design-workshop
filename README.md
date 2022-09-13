# API Design Workshop

intro to api design first and OpenAPI, using OpenAPI at all the phases of your lifecycle including contract testing and simplifying server side code, spectral to make an api style guide so your APIs become eventually consistent whether they’re built yet or not. Then leaving the OpenAPI stuff alone a bit there’s how to make APIs awesome through evolution and depredations, standards that make life easy, all sorts.

## First Challenge: Creating an API

Teacher API - Split up in smaller teams and let each team design one microservice.

Each team will define endpoints, bare minimum entities and relations between entities.

**Tool Suggestions**
  
- [Stoplight Studio](https://stoplight.io/studio) - Web-based is free for one user only. Desktop is free if you give them your email address.
- [Apicur Studio](https://www.apicur.io/studio/) - Web-Based and open-source.
- Various [text editors](https://openapi.tools/#text-editors) on openapi.tools.

**Resources**

- [OpenAPI Documentation](https://github.com/OAI/Documentation/)
- [OpenAPI Specification](https://spec.openapis.org/)

Send a pull request to this repo with the OpenAPI defined as `/apis/team-name/openapi.yaml`.

## Second Challenge: Consuming a Mock

Swap APIs with another team, and pull down their OpenAPI definition. 

Try to interact with their API by looking at their docs, and make a HTTP call to their Mock API.

Create a list of constructive feedback.

**Suggestions**

- Preview docs with `npm install @redocly/cli -g` if you can use NPM, or preview in Stoplight Studio.
- Try multiple mock tools in the team
- Interact with the mock via curl or a simple HTTP client like Insomnia first
- Write code when you have a good HTTP client interaction

**Tool Suggestions**

- [Stoplight Prism](https://stoplight.io/open-source/prism)
- [MockLab](https://www.mocklab.io/docs/getting-started/)
- [OpenAPI Mocker](https://www.npmjs.com/package/open-api-mocker)
- [Sandbox](https://getsandbox.com/)


## Third Challenge (Bonus Round)

Compile a list of feedback and make a written API style guide together.
