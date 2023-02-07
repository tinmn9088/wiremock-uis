# Wiremock for UIS

## Run

Run `docker run -it --rm -p 8080:8080 --name wiremock -v $PWD:/home/wiremock wiremock/wiremock:2.35.0`.

## Mappings

- `/specializations/parents`
- `/specializations/{id}`
- `/specializations/{id}/children`
- `/specializations/search?q=`

## Data

### Specializations

- id: `1000`
  - id: `1011`
    - id: `1056`
    - id: `1058`
  - id: `1012`
- id: `1100`
- id: `1200`
