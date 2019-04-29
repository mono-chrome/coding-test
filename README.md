# Recruitment Test - Data
This is an unattended Front-End recruitment test for TechStyle Fashion Group 

## The Challenge
Create an application to consume one of the APIs listed below and display the Data using [React](https://facebook.github.io/react), [Parcel](https://github.com/parcel-bundler/parcel) or plain compatible JavaScript. Any suitable libraries can be used to achieve this task.

### Requirements
A good solution will
* be production ready
* work on evergreen browsers

### Optional
The following are not required but will be taken into account, if included by the applicant.
* elegant user experience and design
* usage of _appropriate_ front end tooling
* good test coverage

Please put your solution on a repository hosting service such as [GitHub](https://github.com) or [Bitbucket](https://bitbucket.org) (it is always nice to see a clean commit history). Finally, don't forget the README file for your solution.

### Concessions

#### Use of frameworks
Consider the point of the test, it is to get an understanding of your knowledge of the language, libraries and tooling. If you feel you need to use a fully-fledged framework such as [create react app](https://github.com/facebookincubator/create-react-app) or [next.js](https://github.com/zeit/next.js) we cannot determine your understanding of the underlying tooling.

### Data Sources
Select one of the following APIs for your test below.

| API                                                                                  | API Key                          |
|--------------------------------------------------------------------------------------|----------------------------------|
| [Darksky](https://darksky.net/dev) [Doc](https://darksky.net/dev/docs)               | 2531b31fcac013a100c0bbf4eb586d5f |
| - use _Berlin, Germany_ as the location (52.5200° N, 13.4050° E)                     |                                  |
| - display current weather and temperature in Celsius (SI units)                      |                                  |
| [JSON Placeholder](http://jsonplaceholder.typicode.com)                              | N/A                              |
| - use `/albums` and `/photos` in correlation                                         |                                  |
| - display 10 Albums including their photos                                           |                                  |
| [SpaceX](https://api.spacexdata.com/v3/launches) [Doc](https://docs.spacexdata.com/) | N/A                              |
| - display the three most recent launches with the following information              |                                  |
| - Mission Name, Year, Date, Rocket Name and Type, Launch Site                        |                                  |

Please include comments in your source code and add JSDoc if necessary.

*Note:* Darksky has a limited request rate of 1.000 per day. Should you reach that limit under any conditions, please use your own account and secret.

For this basic call example, replace {apiKey} with the key from the table above. Replace {longLat} with the necessary locational Longitude and Latitude.

```
curl -H "Content-Type: application/json" https://api.darksky.net/forecast/{apiKey}/{longLat}
```
