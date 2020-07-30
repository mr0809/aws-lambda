# Paths

## POST /print 

> Prints PDF page from html layout (chrome v83 by default).

**Summary**: Prints PDF page from html layout (chrome v83 by default).

#### Request Body
    
**Content Type**: application/json

**Type**: <code>Object</code>

| Name | Type | Required | Nullable | Description |
| ---- | ---- | -------- | -------- | ----------- |
| source | <code>String</code> | false | false | Optional string to define the source of request |
| html | <code>String</code> | true | false | HTML layout to print |
| pdfSettings | <code>Object</code> | false | false | Optional settings passed to page.pdf() call |

**Example**:

```json
{
  "source": "crude-oil-price-report",
  "html": "<html><head></head><body>test</body></html>",
  "pdfSettings": {
    "width": "100px"
  }
}
```

#### Responses

**Status Code**: 200 - [Success](/content/api/components?id&#x3D;responsessuccess)

* * *

**Status Code**: 400 - [BadRequest](/content/api/components?id&#x3D;responsesbadrequest)

* * *

**Status Code**: 500 - [ServerError](/content/api/components?id&#x3D;responsesservererror)

* * *

## POST /print/chrome/v81 

> Prints PDF page from html layout using chrome v81.

**Summary**: Prints PDF page from html layout using chrome v81.

#### Request Body
    
**Content Type**: application/json

**Type**: <code>Object</code>

| Name | Type | Required | Nullable | Description |
| ---- | ---- | -------- | -------- | ----------- |
| source | <code>String</code> | false | false | Optional string to define the source of request |
| html | <code>String</code> | true | false | HTML layout to print |
| pdfSettings | <code>Object</code> | false | false | Optional settings passed to page.pdf() call |

**Example**:

```json
{
  "source": "crude-oil-price-report",
  "html": "<html><head></head><body>test</body></html>",
  "pdfSettings": {
    "width": "100px"
  }
}
```

#### Responses

**Status Code**: 200 - [Success](/content/api/components?id&#x3D;responsessuccess)

* * *

**Status Code**: 400 - [BadRequest](/content/api/components?id&#x3D;responsesbadrequest)

* * *

**Status Code**: 500 - [ServerError](/content/api/components?id&#x3D;responsesservererror)

* * *

## POST /print/chrome/v83 

> Prints PDF page from html layout using chrome v83.

**Summary**: Prints PDF page from html layout using chrome v83.

#### Request Body
    
**Content Type**: application/json

**Type**: <code>Object</code>

| Name | Type | Required | Nullable | Description |
| ---- | ---- | -------- | -------- | ----------- |
| source | <code>String</code> | false | false | Optional string to define the source of request |
| html | <code>String</code> | true | false | HTML layout to print |
| pdfSettings | <code>Object</code> | false | false | Optional settings passed to page.pdf() call |

**Example**:

```json
{
  "source": "crude-oil-price-report",
  "html": "<html><head></head><body>test</body></html>",
  "pdfSettings": {
    "width": "100px"
  }
}
```

#### Responses

**Status Code**: 200 - [Success](/content/api/components?id&#x3D;responsessuccess)

* * *

**Status Code**: 400 - [BadRequest](/content/api/components?id&#x3D;responsesbadrequest)

* * *

**Status Code**: 500 - [ServerError](/content/api/components?id&#x3D;responsesservererror)

* * *

