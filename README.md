# Backend for Frontend Training, CU Sport Complex Project

Prerequisite:
- Node.js 12.x.x
- Google Cloud SDK
- Yarn
- MongoDB

To deploy:
1. `yarn`.
2. Rename `app.yaml.template` to `app.yaml`.
3. Replace `MONGO_URI` with your own mongo connection uri.
3. Set gcloud project to your own project.
4. `gcloud app deploy`.