# ReCap Frontend — Car Rental Client

An Angular learning client with car, brand, color, customer, rental, and car-detail screens.

Backend: [ReCap Backend](https://github.com/Murat-Selim/Recap_Backend).

## Stack

Angular 11.2, TypeScript 4.1, Bootstrap 5 beta, and RxJS. This repository retains its original course-era dependencies.

## Local setup

Use a Node.js/npm environment compatible with Angular 11 and the committed lockfile.

```sh
git clone https://github.com/Murat-Selim/Recap_Frontend.git
cd Recap_Frontend
npm install
npm start
```

Open `http://localhost:4200`. Start the related backend separately. Service URLs in `src/app/services/` currently target `https://localhost:44375/api/`, matching the backend's IIS Express profile. If you launch the backend with `dotnet run`, update these URLs to its actual port.

## Structure

- `src/app/component/`: car, brand, color, customer, rental, navigation, and detail components.
- `src/app/models/`: API response and domain models.
- `src/app/services/`: backend HTTP clients.

## Validation

```sh
npm run build
npm test
```

Tests use the configured Angular/Karma browser runner. Generated test files do not imply complete user-flow coverage; manually check the affected screen against the backend as well.

## License

No repository-wide license file is currently declared. Retain applicable course and third-party notices.
