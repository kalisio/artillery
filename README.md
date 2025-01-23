# Kalisio fork

This fork aims at easing the usage of [artillery](https://www.artillery.io/) to stress test [feathersjs](https://feathersjs.com/) applications with socketio. In order to achieve this objective, the following changes have been made:
- **emit objects not only strings**,
- **call a processor function to update emitted arguments prior to call**,
- **call a processor function to validate acknowledgment**,
- **call a processor function to validate response**.

> [!NOTE]
> Some information can be found in this [discussion](https://github.com/artilleryio/artillery/discussions/3452)
