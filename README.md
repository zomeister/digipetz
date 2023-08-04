# DIGIPETZ

## setup
Download backend dependencies:
```console
pipenv install
pipenv shell
```
Run backend (Flask API on [`localhost:5555`](http://localhost:5555):
```console
python server/app.py
```

Download frontend dependencies:
```console
npm install --prefix client
```
Run frontend (React app on [`localhost:4000`](http://localhost:4000):
```sh
npm start --prefix client
```

## packages


## models

### `<Owner>`
- id:
- name:

### `<Pet>`
- id:
- name:
- species:

### `<Adoption>`
- id:
- owner_id:
- pet_id:

### `<Action>`
- id:
- adoption_id:

### `<Menu>`
- id:

### `<MenuItem>`
- id:
- menu_id:

