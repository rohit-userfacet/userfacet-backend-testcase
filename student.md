# Student Format

## Request

```json
{
    "full_name": "Shantanu Arora",
    "email_address": "shantanu.arora@gmail.com",
    "weekday": "Monday",
    "start_time": "9 AM",
    "end_time": "10 AM",
}
```

## Response

### Success

```json
{
    "slot_confirmed": "true",
    "weekday": "Monday",
    "start_time": "9 AM",
    "end_time": "10 AM",
    "date": "1 August 2022"
}
```

### Failure

```json
{
    "slot_confirmed": "false",
    "reason": "teacher is not available on this day"
}
```
