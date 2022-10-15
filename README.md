# swift_get_days_between_two_date_obj

```swift
        let calendar = Calendar.current

        // Replace the hour (time) of both dates with 00:00
        
        let date1 = calendar.startOfDay(for: Date(timeIntervalSince1970: 1593785925))
        let date2 = calendar.startOfDay(for: Date())
        let components = calendar.dateComponents([.day], from: date1, to: date2)
        printd("Day Between: \(components)")
```
