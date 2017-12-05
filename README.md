# OTC-Breaks

Web interface with model that identifies break owners in OTC Reconciliations.


## Setup

### Installation


#### Install dependencies

To install Python dependencies, run:
```shell
pip install -r requirements.txt
```

###

### Running the server

Go to http://40.84.53.8:5000/ for OTC Application.


## Example

Here's an example request:


## API

Ensure that the server is running as per above instructions.


### Input

Send a `POST` request to `<HOST>:<PORT>/automobills/api/process_bill` with the `bill` field set to a `*.jpg` or `*.pdf` file.
Ensure that the content type is either `image/jpeg` or `application/pdf`.


### Output

The fields on the bill will be returned in a JSON response.

The API response will contain at least the following fields:

#### Required fields



#### Metadata



### Error Handling

#### Case 1:


#### Case 2:


#### Case 3:
