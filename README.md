endpoint : "https://script.google.com/macros/s/AKfycby7wdgrFnTMT57_VhugVQCu1kYcmuZGKj4iqm2iZVn-qcA7e3PyDtaMoK6vv7aQRYc/exec

# register 
-----
### Endpoint Description

This HTTP POST request is used to send a payload in x-www-form-urlencoded format to the specified URL.

### Request Body

- type (text): Indicates the type of the request.
    
- username (text): Represents the username for authentication.
    
- password (text): Represents the password for authentication.
    

### Response

The response returned is in JSON format with the following schema:

``` json
{
  "success": boolean,
  "message": string
}

 ```

The `success` key indicates the success status of the request, and the `message` key provides any additional message or information.

# Login Request
-----
### Endpoint Description

This HTTP POST request is used to send a payload in x-www-form-urlencoded format to the specified URL.

### Request Body

- type (text):
    
    - Description: Indicates the type of the request.
        
- username (text):
    
    - Description: Represents the username for authentication.
        
- password (text):
    
    - Description: Represents the password for authentication.
        

### Response

The response returned is in JSON format with the following schema:

``` json
{
  "success": boolean,
  "message": string,
  "token": string
}

 ```

- success (boolean): Indicates the success status of the request.
    
- message (string): Provides any additional message or information.
    
- token (string): Represents the token (JWT) received upon successful execution.
