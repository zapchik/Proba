FROM cypress/included:4.1.0
WORKDIR /app
COPY ./cypress ./cypress
COPY ./cypress.json ./cypress.json
COPY ./cypress.env.json ./cypress.env.json
EXPOSE 80
RUN npx cypress open
