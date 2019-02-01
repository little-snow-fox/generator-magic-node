<h1 align="center">generator-magic-node</h1>
<p align="center">
    <a href="https://opensource.org/licenses/MIT"     rel="nofollow">
        <img src="https://camo.githubusercontent.com/9a140a4c68e7c178bc660bee7675f4f25ff7ade3/68747470733a2f2f696d672e736869656c64732e696f2f6e706d2f6c2f7675652e737667" alt="License" data-canonical-src="https://img.shields.io/npm/l/vue.svg" style="max-width:100%;">
    </a>
    <a href="https://www.npmjs.com/package/generator-magic-node"     rel="nofollow">
        <img src="https://img.shields.io/npm/v/generator-magic-node.svg" alt="npm" data-canonical-src="https://img.shields.io/npm/v/generator-magic-node.svg" style="max-width:100%;">
    </a>
    <a href="https://github.com/little-snow-fox/generator-magic-node/blob/master/README.md"     rel="nofollow">
        <img src="https://camo.githubusercontent.com/de158aa34a13afbb30d42288888cf9aa1d29a9d7/68747470733a2f2f696d672e736869656c64732e696f2f6769747465722f726f6f6d2f616e742d64657369676e2f616e742d64657369676e2d656e676c6973682e7376673f7374796c653d666c61742d737175617265266c6f676f57696474683d3230266c6f676f3d64617461253341696d616765253246737667253242786d6c2533426261736536342532435044393462577767646d567963326c76626a30694d5334774969426c626d4e765a476c755a7a3069565652474c546769507a344e436a787a646d636765473173626e4d39496d6830644841364c79393364336375647a4d7562334a6e4c7a49774d44417663335a6e4969423462577875637a703462476c75617a30696148523063446f764c336433647935334d793576636d63764d546b354f53393462476c756179496764326c6b64476739496a45794d7a55694947686c6157646f644430694e6a55774969423261575633516d393450534977494441674e7a51784d43417a4f544177496a344e436a78795a574e30494864705a48526f505349334e4445774969426f5a576c6e61485139496a4d354d44416949475a706247773949694e694d6a49794d7a51694c7a344e436a78775958526f49475139496b30774c4451314d4567334e444577625441734e6a4177534442744d4377324d4442494e7a51784d4730774c4459774d456777625441734e6a4177534463304d5442744d4377324d4442494d434967633352796232746c5053496a5a6d5a6d4969427a64484a766132557464326c6b64476739496a4d774d4349765067304b50484a6c5933516764326c6b64476739496a49354e6a51694947686c6157646f644430694d6a45774d4349675a6d6c7362443069497a4e6a4d3249325a5349765067304b504763675a6d6c736244306949325a6d5a694925324244516f385a7942705a443069637a4534496a344e436a786e49476c6b50534a7a4f534925324244516f385a7942705a443069637a55695067304b5047636761575139496e4d30496a344e436a78775958526f49476c6b50534a7a4969426b50534a4e4d6a51334c446b7749444d784e7934314d7a51794d7a41734d7a41334c6a41344d6a417a4f5341784d7a49754f44637a4d6a45344c4445334d6934354d5463354e6a46494d7a59784c6a45794e6a63344d6b77784e7a59754e4459314e7a63774c444d774e7934774f4449774d7a6c3649693825324244516f3864584e6c49486873615735724f6d68795a57593949694e7a49694235505349304d6a41694c7a344e436a78316332556765477870626d733661484a6c5a6a306949334d6949486b39496a67304d4349765067304b5048567a5a53423462476c75617a706f636d566d5053496a63794967655430694d5449324d4349765067304b5043396e5067304b5048567a5a53423462476c75617a706f636d566d5053496a63794967655430694d5459344d4349765067304b5043396e5067304b5048567a5a53423462476c75617a706f636d566d5053496a637a516949486739496a49304e794967655430694d6a457749693825324244516f384c326325324244516f3864584e6c49486873615735724f6d68795a57593949694e7a4f534967654430694e446b3049693825324244516f384c326325324244516f3864584e6c49486873615735724f6d68795a57593949694e7a4d54676949486739496a6b344f4349765067304b5048567a5a53423462476c75617a706f636d566d5053496a637a6b6949486739496a45354e7a59694c7a344e436a78316332556765477870626d733661484a6c5a6a306949334d3149694234505349794e44637749693825324244516f384c326325324244516f384c334e325a7a34253344" alt="Gitter" data-canonical-src="https://img.shields.io/gitter/room/ant-design/ant-design-english.svg?style=flat-square&amp;logoWidth=20&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4NCjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgd2lkdGg9IjEyMzUiIGhlaWdodD0iNjUwIiB2aWV3Qm94PSIwIDAgNzQxMCAzOTAwIj4NCjxyZWN0IHdpZHRoPSI3NDEwIiBoZWlnaHQ9IjM5MDAiIGZpbGw9IiNiMjIyMzQiLz4NCjxwYXRoIGQ9Ik0wLDQ1MEg3NDEwbTAsNjAwSDBtMCw2MDBINzQxMG0wLDYwMEgwbTAsNjAwSDc0MTBtMCw2MDBIMCIgc3Ryb2tlPSIjZmZmIiBzdHJva2Utd2lkdGg9IjMwMCIvPg0KPHJlY3Qgd2lkdGg9IjI5NjQiIGhlaWdodD0iMjEwMCIgZmlsbD0iIzNjM2I2ZSIvPg0KPGcgZmlsbD0iI2ZmZiI%2BDQo8ZyBpZD0iczE4Ij4NCjxnIGlkPSJzOSI%2BDQo8ZyBpZD0iczUiPg0KPGcgaWQ9InM0Ij4NCjxwYXRoIGlkPSJzIiBkPSJNMjQ3LDkwIDMxNy41MzQyMzAsMzA3LjA4MjAzOSAxMzIuODczMjE4LDE3Mi45MTc5NjFIMzYxLjEyNjc4MkwxNzYuNDY1NzcwLDMwNy4wODIwMzl6Ii8%2BDQo8dXNlIHhsaW5rOmhyZWY9IiNzIiB5PSI0MjAiLz4NCjx1c2UgeGxpbms6aHJlZj0iI3MiIHk9Ijg0MCIvPg0KPHVzZSB4bGluazpocmVmPSIjcyIgeT0iMTI2MCIvPg0KPC9nPg0KPHVzZSB4bGluazpocmVmPSIjcyIgeT0iMTY4MCIvPg0KPC9nPg0KPHVzZSB4bGluazpocmVmPSIjczQiIHg9IjI0NyIgeT0iMjEwIi8%2BDQo8L2c%2BDQo8dXNlIHhsaW5rOmhyZWY9IiNzOSIgeD0iNDk0Ii8%2BDQo8L2c%2BDQo8dXNlIHhsaW5rOmhyZWY9IiNzMTgiIHg9Ijk4OCIvPg0KPHVzZSB4bGluazpocmVmPSIjczkiIHg9IjE5NzYiLz4NCjx1c2UgeGxpbms6aHJlZj0iI3M1IiB4PSIyNDcwIi8%2BDQo8L2c%2BDQo8L3N2Zz4%3D" style="max-width:100%;">
    </a>
    <a href="https://github.com/little-snow-fox/generator-magic-node/blob/master/README-zh_CN.md"     rel="nofollow">
        <img src="https://camo.githubusercontent.com/73aaab2084d86ec4b409c7824ec10a617a543bd6/68747470733a2f2f696d672e736869656c64732e696f2f6769747465722f726f6f6d2f616e742d64657369676e2f616e742d64657369676e2e7376673f7374796c653d666c61742d737175617265266c6f676f57696474683d3230266c6f676f3d64617461253341696d616765253246737667253242786d6c2533426261736536342532435044393462577767646d567963326c76626a30694d5334774969426c626d4e765a476c755a7a3069565652474c546769507a344e436a787a646d636765473173626e4d39496d6830644841364c79393364336375647a4d7562334a6e4c7a49774d44417663335a6e4969423462577875637a703462476c75617a30696148523063446f764c336433647935334d793576636d63764d546b354f53393462476c756179496764326c6b64476739496a6b774d434967614756705a326830505349324d44416949485a705a58644362336739496a41674d43417a4d4341794d434925324244516f385a47566d637a344e436a78775958526f49476c6b50534a7a4969426b50534a4e4d4377744d5341774c6a55344e7a63344e5377774c6a67774f5441784e7941744d4334354e5445774e5463734c5441754d7a41354d444533534441754f5455784d445533544330774c6a55344e7a63344e5377774c6a67774f5441784e336f6949475a706247773949694e6d5a6d526c4d4441694c7a344e436a77765a47566d637a344e436a78795a574e30494864705a48526f5053497a4d434967614756705a326830505349794d4349675a6d6c73624430694932526c4d6a6b784d4349765067304b5048567a5a53423462476c75617a706f636d566d5053496a6379496764484a68626e4e6d62334a7450534a30636d4675633278686447556f4e5377314b53427a593246735a53677a4b5349765067304b5048567a5a53423462476c75617a706f636d566d5053496a6379496764484a68626e4e6d62334a7450534a30636d4675633278686447556f4d5441734d696b67636d39305958526c4b44497a4c6a417a4e6a49304d796b694c7a344e436a78316332556765477870626d733661484a6c5a6a306949334d69494852795957357a5a6d39796254306964484a68626e4e735958526c4b4445794c44517049484a76644746305a5367304e5334344e6a6b344f54677049693825324244516f3864584e6c49486873615735724f6d68795a57593949694e7a49694230636d467563325a76636d3039496e52795957357a624746305a5367784d6977334b534279623352686447556f4e6a6b754f5451314d7a6b324b5349765067304b5048567a5a53423462476c75617a706f636d566d5053496a6379496764484a68626e4e6d62334a7450534a30636d4675633278686447556f4d5441734f536b67636d39305958526c4b4449774c6a59314f5467774f436b694c7a344e436a777663335a6e5067253344253344" alt="Join the chat at https://gitter.im/ant-design/ant-design" data-canonical-src="https://img.shields.io/gitter/room/ant-design/ant-design.svg?style=flat-square&amp;logoWidth=20&amp;logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPD94bWwgdmVyc2lvbj0iMS4wIiBlbmNvZGluZz0iVVRGLTgiPz4NCjxzdmcgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiB4bWxuczp4bGluaz0iaHR0cDovL3d3dy53My5vcmcvMTk5OS94bGluayIgd2lkdGg9IjkwMCIgaGVpZ2h0PSI2MDAiIHZpZXdCb3g9IjAgMCAzMCAyMCI%2BDQo8ZGVmcz4NCjxwYXRoIGlkPSJzIiBkPSJNMCwtMSAwLjU4Nzc4NSwwLjgwOTAxNyAtMC45NTEwNTcsLTAuMzA5MDE3SDAuOTUxMDU3TC0wLjU4Nzc4NSwwLjgwOTAxN3oiIGZpbGw9IiNmZmRlMDAiLz4NCjwvZGVmcz4NCjxyZWN0IHdpZHRoPSIzMCIgaGVpZ2h0PSIyMCIgZmlsbD0iI2RlMjkxMCIvPg0KPHVzZSB4bGluazpocmVmPSIjcyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoNSw1KSBzY2FsZSgzKSIvPg0KPHVzZSB4bGluazpocmVmPSIjcyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTAsMikgcm90YXRlKDIzLjAzNjI0MykiLz4NCjx1c2UgeGxpbms6aHJlZj0iI3MiIHRyYW5zZm9ybT0idHJhbnNsYXRlKDEyLDQpIHJvdGF0ZSg0NS44Njk4OTgpIi8%2BDQo8dXNlIHhsaW5rOmhyZWY9IiNzIiB0cmFuc2Zvcm09InRyYW5zbGF0ZSgxMiw3KSByb3RhdGUoNjkuOTQ1Mzk2KSIvPg0KPHVzZSB4bGluazpocmVmPSIjcyIgdHJhbnNmb3JtPSJ0cmFuc2xhdGUoMTAsOSkgcm90YXRlKDIwLjY1OTgwOCkiLz4NCjwvc3ZnPg%3D%3D" style="max-width:100%;">
    </a>
</p>
<div align="center">
    English | <a href="https://github.com/little-snow-fox/generator-magic-node/blob/master/README-zh_CN.md">简体中文</a>
</div>

# Describe    
This is a node back-end service generator that generates scaffolding and entity classes.   

In order to ensure that the background required for a set of front-end projects can switch seamlessly between jhipster and nodejs, the interface specification and jhipster are as consistent as possible, including authorization and authentication methods.

# Conditions  
1. yeoman needs to be installed.
```
npm install -g yo
```
2. The entity class generation section requires the JSON file generated using [JDL], Those who are not familiar with [JDL](https://www.jhipster.tech/jdl) can find relevant documents and help on [jhipster](https://www.jhipster.tech) official website.   
```
npm install -g generator-jhipster
```

# Install      
```
npm install -g generator-magic-node
```

# Use    
* Generating scaffold.
```
mkdir node-project
cd node-project
yo magic-node
```

* Generating entity classes.
1. Please go to [jdl-studio](https://start.jhipster.tech/jdl-studio) to write the data table and export it to the project root directory. For example, the file I exported is jhipster-jdl.jh
    ```
        cp jhipster-jdl.jh node-project/jhipster-jdl.jh
        cd node-project
        jhipster import-jdl jhipster-jdl.jh
    ```
    After successful execution, .jhipster folder will appear in the current project file directory.

2. Execute the command to generate the entity class.
    ```
    yo magic-node --lang=zh --entity=Region
    ```
    Or
    ```
    yo magic-node
    language[en/zh/ja] en
    What generates? Entity class
    Entity name: Region
    ```
3. Run project.
    ```
    npm install tsc -g
    npm install
    npm run start
    ```

# Directory structure
```
.directory
.gitignore
.jhipster   # Data model config.
│-- Region.json 
.yo-rc.json
README.md
config.json
ormconfig.json
package.json
src
│-- controller  # Control layer, interface entry.
│-- entity  # Entity layer, data model class location.
│-- enum  # Enum class.
│-- index.ts
│-- middleware
│-- migration
│-- sample  # Sample data for automatically creating template data at project startup.
│-- subscriber
│-- util
tsconfig.json
```
# Generated control layer example
```
import { Context } from 'koa';
import { getManager } from 'typeorm';
import Region from '../entity/Region';
import { validate } from 'class-validator';
import Elastic from '../util/Elastic';
import { setRoute, RequestMethod } from '../middleware/Routes';
import { getElasticSearchParams, setElasticSearchPagingHeader, deleteSuccessfulResponse, getRequestParamId } from '../util/Tools';
import { BadRequestAlertException, NotFoundAlertException } from '../middleware/RequestError';

export default class RegionAction {
  /**
   * get
   * @param {Application.Context} context
   * @param decoded
   * @returns {Promise<void>}
   */
  @setRoute('/api/regions/:id')
  async getRegion(context: Context, decoded?: any) {
    const id = getRequestParamId(context);
    const regionRepository = getManager().getRepository(Region);
    const region: Region = await regionRepository.findOne(id);
    if (region) {
      context.body = region;
    } else {
      throw new NotFoundAlertException();
    }
  }
  /**
   * post
   * @param {Application.Context} context
   * @param decoded
   * @returns {Promise<void>}
   */
  @setRoute('/api/regions', RequestMethod.POST)
  async createRegion(context: Context, decoded?: any) {
    const regionRepository = getManager().getRepository(Region);
    const region: Region = regionRepository.create(<Region>{
      ...context.request.body
    });
    const errors = await validate(region);
    if (errors.length > 0) {
      throw new BadRequestAlertException(null, errors);
    } else {
      await getManager().save(region);
      await Elastic.syncCreate(region.id, regionRepository.metadata.tableName);
      context.body = region;
    }
  }
  /**
   * put
   * @param {Application.Context} context
   * @param decoded
   * @returns {Promise<void>}
   */
  @setRoute('/api/regions', RequestMethod.PUT)
  async updateRegion(context: Context, decoded?: any) {
    const regionRepository = getManager().getRepository(Region);
    const region: Region = regionRepository.create(<Region>{
      ...context.request.body
    });
    const errors = await validate(region);
    if (errors.length > 0) {
      throw new BadRequestAlertException(null, errors);
    } else {
      await regionRepository.update(region.id, region);
      await Elastic.syncUpdate(region.id, regionRepository.metadata.tableName);
      context.body = region;
    }
  }
  /**
   * delete
   * @param {Application.Context} context
   * @param decoded
   * @returns {Promise<void>}
   */
  @setRoute('/api/regions/:id', RequestMethod.DELETE)
  async deleteRegion(context: Context, decoded?: any) {
    const id = getRequestParamId(context);
    const regionRepository = getManager().getRepository(Region);
    await regionRepository.delete(id);
    await Elastic.syncDelete(id, regionRepository.metadata.tableName);
    deleteSuccessfulResponse(context, id)
  }
  /**
   * search
   * @param {Application.Context} context
   * @param decoded
   * @returns {Promise<void>}
   */
  @setRoute('/api/_search/regions')
  async searchRegion(context: Context, decoded?: any) {
    const res: any = await Elastic.search(getElasticSearchParams(context), 'region');
    setElasticSearchPagingHeader(context, res);
    context.body = res.data;
  }
}

``` 

# Interface example
* Create  
    Request:

    ```
    curl --request POST \
    --url http://localhost:3000/api/regions \
    --header 'cache-control: no-cache' \
    --header 'content-type: application/json' \
    --header 'postman-token: 137cfaa2-bba3-94c6-a73d-858bf899f3c7' \
    --data '{\n	"regionName": "CN"\n}'
    ```
    ```
    POST /api/regions HTTP/1.1
    Host: localhost:3000
    Content-Type: application/json
    Cache-Control: no-cache
    Postman-Token: ffe8ff8c-f9e2-60be-dc1a-0f7e5e2b2383

    {
        "regionName": "CN"
    }
    ```
    Response:
    ```
    {
        "regionName": "CN",
        "id": 1
    }
    ```
* Change  
    Request:
    ```
    curl --request PUT \
    --url http://localhost:3000/api/regions \
    --header 'cache-control: no-cache' \
    --header 'content-type: application/json' \
    --header 'postman-token: e4cae952-07bc-0857-73be-9d2099d3954f' \
    --data '{\n	"id": 1,\n	"regionName": "JP"\n}'
    ```
    ```
    PUT /api/regions HTTP/1.1
    Host: localhost:3000
    Content-Type: application/json
    Cache-Control: no-cache
    Postman-Token: 604881ef-c221-f756-e3c5-6e1e58163b6c

    {
	    "id": 1,
	    "regionName": "JP"
    }
    ```
    Response:
    ```
    {
        "id": 1,
        "regionName": "JP"
    }
    ```
* Delete  
    Request:
    ```
    curl --request DELETE \
    --url http://localhost:3000/api/regions/1 \
    --header 'cache-control: no-cache' \
    --header 'content-type: application/json' \
    --header 'postman-token: d0bd6631-b56d-3c14-565a-f1a6d14aba47'
    ```
    ```
    DELETE /api/regions/1 HTTP/1.1
    Host: localhost:3000
    Content-Type: application/json
    Cache-Control: no-cache
    Postman-Token: 70b023ea-b101-c46e-9240-90f1909c2107
    ```
    Response:
    ```
    {
        "id": "1"
    }
    ```
* Get  
    Request:
    ```
    curl --request GET \
    --url http://localhost:3000/api/regions/1 \
    --header 'cache-control: no-cache' \
    --header 'content-type: application/json' \
    --header 'postman-token: 32045bad-4ed5-fbfa-4a7f-9b2686eb3891'
    ```
    ```
    GET /api/regions/1 HTTP/1.1
    Host: localhost:3000
    Content-Type: application/json
    Cache-Control: no-cache
    Postman-Token: ca50cf1d-7e72-70a2-37c8-037bfcc5893f

    ```
    Response:
    ```
    {
        "id": 1,
        "regionName": "CN"
    }
    ```
* Search (use Elasticsearch)  
    Query parameters:    
    * query: Query string, please go to [elastic](https://www.elastic.co) for relevant documents.
    * page: Page index, Starting from the 0, default 0.
    * size: Page size, default 0.
    * sort: Sort，Please go to [elastic](https://www.elastic.co) for relevant documents.

    Request:  
    ```
    curl --request GET \
    --url 'http://localhost:3000/api/_search/regions?query=regionName%3ACN&page=0&size=10' \
    --header 'cache-control: no-cache' \
    --header 'content-type: application/json' \
    --header 'postman-token: 12afa220-9d89-6f7c-97b9-1dde9f4c8c85'
    ```
    ```
    GET /api/_search/regions?query=regionName:CN&amp;page=0&amp;size=10 HTTP/1.1
    Host: localhost:3000
    Content-Type: application/json
    Cache-Control: no-cache
    Postman-Token: 260f20fc-4697-51a1-38cb-ceeb4259ea23
    ```
    Response:    
    header  
    ```
    x-page: 0
    x-size: 10
    x-total-count: 1
    ```
    body  
    ```
    [
        {
            "id": 1,
            "regionName": "CN"
        }
    ]
    ```
* Search (use Mysql)  
    Query parameters:   
    * *.equals: Condition, example: regionName.equals=CN.
    * *.contains: Condition.
    * *.in: Condition, example.in=1,2,3.
    * *.specified: Condition, example: name.specified=true.
    * *.greaterOrEqualThan: Condition, example: id.greaterOrEqualThan=2.
    * *.greaterThan: Condition.
    * *.lessOrEqualThan: Condition.
    * *.lessThan: Condition.
    * page: Page index, Starting from the 0, default 0.
    * size: Page size, default 0.
    * sort: Sort, example: sort=id,DESC&sort=regionName,ASC

    Request:  
    ```
    curl --request GET \
    --url 'http://localhost:3000/api/_search/regions?regionName.equals=CN&sort=id%2CDESC&page=0&size=10' \
    --header 'cache-control: no-cache' \
    --header 'content-type: application/json' \
    --header 'postman-token: 2bee9d1e-d406-a8fc-47fb-01f0cd5a661a'
    ```
    ```
    GET /api/_search/regions?regionName.equals=CN&amp;sort=id,DESC&amp;page=0&amp;size=10 HTTP/1.1
    Host: localhost:3000
    Content-Type: application/json
    Cache-Control: no-cache
    Postman-Token: 88a2fc33-7d21-7395-ee59-d09c2399c571
    ```
    Response:    
    header  
    ```
    x-page: 0
    x-size: 10
    x-total-count: 1
    ```
    body  
    ```
    [
        {
            "id": 1,
            "regionName": "CN"
        }
    ]
    ```
# Login 
Authorize the use of the JWT protocol, The interface is the same as jhipster's JWT authorized login interface.
* Get Token  
    Request:
    ```
    curl --request POST \
    --url http://localhost:3000/api/authenticate \
    --header 'cache-control: no-cache' \
    --header 'content-type: application/json' \
    --header 'postman-token: dd8547b8-5c18-e5b1-e0e9-621de99914f1' \
    --data '{\n	"password": "admin",\n	"username": "admin"\n}'
    ```
    ```
    POST /api/authenticate HTTP/1.1
    Host: localhost:3000
    Content-Type: application/json
    Cache-Control: no-cache
    Postman-Token: 53e4cacc-d444-ed3c-be50-c107693b8d1e

    {
	    "password": "admin",
	    "username": "admin"
    }
    ```
    Response:
    ```
    {
        "id_token": "eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyIjp7ImlkIjozLCJsb2dpbiI6ImFkbWluIiwiZmlyc3ROYW1lIjoiQWRtaW5pc3RyYXRvciIsImxhc3ROYW1lIjoiQWRtaW5pc3RyYXRvciIsImVtYWlsIjoiYWRtaW5AbG9jYWxob3N0IiwiaW1hZ2VVcmwiOiJodHRwczovL3dwaW1nLndhbGxzdGNuLmNvbS9mNzc4NzM4Yy1lNGY4LTQ4NzAtYjYzNC01NjcwM2I0YWNhZmUuZ2lmP2ltYWdlVmlldzIvMS93LzgwL2gvODAiLCJhY3RpdmF0ZWQiOjEsImxhbmdLZXkiOiJlbiIsImFjdGl2YXRpb25LZXkiOm51bGwsInJlc2V0S2V5IjpudWxsLCJjcmVhdGVkQnkiOiJzeXN0ZW0iLCJjcmVhdGVkRGF0ZSI6bnVsbCwicmVzZXREYXRlIjpudWxsLCJsYXN0TW9kaWZpZWRCeSI6InN5c3RlbSIsImxhc3RNb2RpZmllZERhdGUiOm51bGx9LCJhdXRob3JpdGllcyI6WyJST0xFX0FETUlOIiwiUk9MRV9VU0VSIl0sImlhdCI6MTU0ODM5OTQzNCwiZXhwIjoxNTQ5Njk1NDM0fQ.9y9YOKtJaT33T56A2mKKrSeI0ojCmUFPU5JxvLNR3ds"
    }
    ```
* Get Account info  
    Request: 
    ```
    curl --request GET \
    --url http://localhost:3000/api/account \
    --header 'authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyIjp7ImlkIjozLCJsb2dpbiI6ImFkbWluIiwiZmlyc3ROYW1lIjoiQWRtaW5pc3RyYXRvciIsImxhc3ROYW1lIjoiQWRtaW5pc3RyYXRvciIsImVtYWlsIjoiYWRtaW5AbG9jYWxob3N0IiwiaW1hZ2VVcmwiOiJodHRwczovL3dwaW1nLndhbGxzdGNuLmNvbS9mNzc4NzM4Yy1lNGY4LTQ4NzAtYjYzNC01NjcwM2I0YWNhZmUuZ2lmP2ltYWdlVmlldzIvMS93LzgwL2gvODAiLCJhY3RpdmF0ZWQiOjEsImxhbmdLZXkiOiJlbiIsImFjdGl2YXRpb25LZXkiOm51bGwsInJlc2V0S2V5IjpudWxsLCJjcmVhdGVkQnkiOiJzeXN0ZW0iLCJjcmVhdGVkRGF0ZSI6bnVsbCwicmVzZXREYXRlIjpudWxsLCJsYXN0TW9kaWZpZWRCeSI6InN5c3RlbSIsImxhc3RNb2RpZmllZERhdGUiOm51bGx9LCJhdXRob3JpdGllcyI6WyJST0xFX0FETUlOIiwiUk9MRV9VU0VSIl0sImlhdCI6MTU0ODM5OTQzNCwiZXhwIjoxNTQ5Njk1NDM0fQ.9y9YOKtJaT33T56A2mKKrSeI0ojCmUFPU5JxvLNR3ds' \
    --header 'cache-control: no-cache' \
    --header 'postman-token: bc7974d7-c9ff-8ccb-1037-0efdb099db88'
    ```
    ```
    GET /api/account HTTP/1.1
    Host: localhost:3000
    Authorization: Bearer eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJ1c2VyIjp7ImlkIjozLCJsb2dpbiI6ImFkbWluIiwiZmlyc3ROYW1lIjoiQWRtaW5pc3RyYXRvciIsImxhc3ROYW1lIjoiQWRtaW5pc3RyYXRvciIsImVtYWlsIjoiYWRtaW5AbG9jYWxob3N0IiwiaW1hZ2VVcmwiOiJodHRwczovL3dwaW1nLndhbGxzdGNuLmNvbS9mNzc4NzM4Yy1lNGY4LTQ4NzAtYjYzNC01NjcwM2I0YWNhZmUuZ2lmP2ltYWdlVmlldzIvMS93LzgwL2gvODAiLCJhY3RpdmF0ZWQiOjEsImxhbmdLZXkiOiJlbiIsImFjdGl2YXRpb25LZXkiOm51bGwsInJlc2V0S2V5IjpudWxsLCJjcmVhdGVkQnkiOiJzeXN0ZW0iLCJjcmVhdGVkRGF0ZSI6bnVsbCwicmVzZXREYXRlIjpudWxsLCJsYXN0TW9kaWZpZWRCeSI6InN5c3RlbSIsImxhc3RNb2RpZmllZERhdGUiOm51bGx9LCJhdXRob3JpdGllcyI6WyJST0xFX0FETUlOIiwiUk9MRV9VU0VSIl0sImlhdCI6MTU0ODM5OTQzNCwiZXhwIjoxNTQ5Njk1NDM0fQ.9y9YOKtJaT33T56A2mKKrSeI0ojCmUFPU5JxvLNR3ds
    Cache-Control: no-cache
    Postman-Token: 0697e795-506d-fb51-f35a-cf6009437a8d

    ```
    Response:
    ```
    {
        "id": 3,
        "login": "admin",
        "firstName": "Administrator",
        "lastName": "Administrator",
        "email": "admin@localhost",
        "imageUrl": "https://wpimg.wallstcn.com/f778738c-e4f8-4870-b634-56703b4acafe.gif?imageView2/1/w/80/h/80",
        "activated": 1,
        "langKey": "en",
        "activationKey": null,
        "resetKey": null,
        "createdBy": "system",
        "createdDate": null,
        "resetDate": null,
        "lastModifiedBy": "system",
        "lastModifiedDate": null,
        "authorities": [
            "ROLE_ADMIN",
            "ROLE_USER"
        ]
    }
    ```

# Technology stack   

<a href="https://nodejs.org">
    <img src="https://raw.githubusercontent.com/little-snow-fox/images/master/logos/node.png" width="20%">
</a>
<a href="https://github.com/koajs/koa">
    <img src="https://raw.githubusercontent.com/koajs/koa/HEAD/docs/logo.png" width="20%">
</a>
<a href="https://www.tslang.cn">
    <img src="https://raw.githubusercontent.com/little-snow-fox/images/master/logos/typescript.png" width="20%">
</a>
<a href="http://typeorm.io">
    <img src="https://raw.githubusercontent.com/little-snow-fox/images/master/logos/typeorm.png" width="20%">
</a>
<a href="https://www.mysql.com">
    <img src="https://raw.githubusercontent.com/little-snow-fox/images/master/logos/mysql.png" width="20%">
</a>
<a href="https://www.elastic.co">
    <img src="https://raw.githubusercontent.com/little-snow-fox/images/master/logos/elastic.png" width="20%">
</a>
<a href="https://yeoman.io">
    <img src="https://raw.githubusercontent.com/little-snow-fox/images/master/logos/yeoman.png" width="20%">
</a>

# License  
MIT © [snowfox](https://github.com/little-snow-fox)
