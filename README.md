# Frontend

## APIs
The default port of this component is ```8000```. The default port can be changed with the ```ROCKET_PORT``` environment variable. 

### Frontend
The following endpoints are available:
- GET ```/```: base website
- GET ```/stats/data```: A statistical representation of the colors returned by the backend
- GET ```stats/show```: A visual representation of the stats from ```/stats/data```
- GET ```/load/start```: Starts creating load for the backend
- GET ```/load/stop```: Stops creating load for the backend
