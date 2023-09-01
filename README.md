# Smart-House

### Description
The application aims to simplify the process of room and device management in a smart home. Users can create rooms, add devices to each room, and manipulate device states. Each room can be colored for easy identification. Devices within rooms can be turned on or off with a single click. The application also supports deletion of rooms and devices.

### Features

1. **Room Management**: Create new rooms with customizable names and colors.
2. **Device Management**: Add different types of devices like "Air Conditioner," "Boiler," "Stereo System," and "Light" to rooms.
3. **Interactive UI**: Use buttons to interact with devices within rooms, switching their states between 'on' and 'off'.
4. **Validation**: Checks for duplicate room names and devices, as well as validates input for required fields.
5. **Context Sharing**: Uses custom React Context API to share state between different components for more streamlined state management.
6. **Routing**: Utilizes `react-router-dom` for navigating between different components/pages.
7. **Deletion**: Allows users to delete rooms and devices.
8. **Dynamic UI**: The UI reflects the state of devices in real-time, color-coding devices based on their 'on' or 'off' status.
9. **Consumer Pattern**: Uses the Context Consumer pattern to read values from the custom Context API.

### Technologies Used

1. **React**: For building the user interface.
2. **React Router**: Used for client-side routing.
3. **React Context API**: Used for state management across components.
4. **JavaScript (ES6)**: For client-side scripting.
5. **CSS**: For styling the components.

