# Weather-iOS15

## What We Will Create

We’re going to make a Weather App. You will be able to see the weather in different cities and even in your location using APIs and Networking!

## What You'll Learn

You will learn about Dark Mode and Vector Assets, Protocols & The Delegate Design Pattern, Understanding APIs and URL Parameters, and much more. 

>This is a project from the iCodeLife iOS 15 & Swift Course, check out the full course at [www.icodelife.com/courses](https://www.icodelife.com/courses)

### Condition Codes
```
switch conditionID {
        case 200...232:
            return "cloud.bolt"
        case 300...321:
            return "cloud.drizzle"
        case 500...531:
            return "cloud.rain"
        case 600...622:
            return "cloud.snow"
        case 701...781:
            return "cloud.fog"
        case 800:
            return "sun.max"
        case 801...804:
            return "cloud.bolt"
        default:
            return "cloud"
        }
```
