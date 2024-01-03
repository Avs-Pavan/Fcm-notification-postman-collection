# FCM Notifications Postman Collection

This Postman collection provides examples for sending different types of Firebase Cloud Messaging (FCM) notifications. Use these requests as templates to interact with the FCM API for sending notifications to Android and iOS devices.

## Collection Details

- **Postman Collection Name:** FCM Notifications
- **Postman Collection ID:** 32ca9fd9-b938-4a72-8466-d9ebe07b466a

## Usage Guide

### 1. Update Server Key

Before using these requests, ensure that you have the correct FCM Server Key. Follow these steps to update the Server Key:

1. Go to the [Firebase Console](https://console.firebase.google.com/).
2. Select your project.
3. Navigate to Project settings.
4. In the Cloud Messaging tab, find the "Server key" under the Project credentials section.
5. Update the `"Authorization"` header in each request with the new Server Key.

### 2. Update FCM Token

Update the FCM token with the specific token of the target device you want to send the notification to. Replace the existing token in the `to` field of each request with the FCM token of your target device.

### 3. Update FCM Topic

For requests related to FCM topics, update the topic name as needed. Replace the existing topic name in the `to` field of each request with the desired FCM topic.

## Request Descriptions

1. **Data Payload Notification**
   - Sends a notification with a data payload containing a title and body.

2. **Simple Notification**
   - Sends a simple notification with a title and body.

3. **Composite Notification**
   - Sends a notification with both a data payload and a simple notification.

4. **Topic Notification**
   - Sends a notification to a specific FCM topic with a data payload.

## Sending Requests

1. Open Postman.
2. Import this collection using the provided collection ID.
3. Update the Server Key, FCM token, and FCM topic as needed in each request.
4. Send the requests to the FCM API for testing.

Feel free to customize the notification content and data payload according to your application's requirements. For more information on FCM, refer to the [Firebase Cloud Messaging Documentation](https://firebase.google.com/docs/cloud-messaging).
