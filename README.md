# Basic Express Server

### Author: Mark Duenas

[Deployed Link Using GUI](http://cloudservertest-env.eba-fetsd2uu.us-west-2.elasticbeanstalk.com/person?name=Mark)
[Deployed Link Using CLI](http://cloud-server-part2-dev.us-west-2.elasticbeanstalk.com/person?name=Mark)

[Pull Req](https://github.com/MarkDuenas/basic-express-server/pull/3)

## Set up

`.env` requirements

- PORT - Port Number

### Running the app

    - npm start
    - Endpoint: /person?name=YOURNAMEHERE
      - Returns JSON Object

        ```
        {
          "name":"Jack"
        }
        ```

### Tests

    - Server Tests: `npm run test`
