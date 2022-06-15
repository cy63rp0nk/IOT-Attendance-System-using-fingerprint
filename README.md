# IOT-Attendance-System-using-fingerprint
An IFTTT server is used to create a webhook to update the attendance register created in google sheets on recognition of an enrolled fingerprint using an ESP 32 module.


enroll.ino file is used to register/enroll fingerprints into memory.

On successful registration the fingerprint_attendance.ino file can be run to detect and update attendance to an attached google sheets using the webhook created using
the IFTTT server.

Fingerprint detection is set to be an event to trigger the updation of attenance in google sheets.
