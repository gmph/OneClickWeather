# One-Click Weather
One-Click Weather is a really simple web app that lets you check the weather where you are.

## Design

I designed the page to be ridiculously minimal but spent a lot of time making sure the animations and UX flowed well. The design and animations are based on Material design. Though the app is simple, I tested edge-cases and errors to make sure it always feels nice – let me know if you notice any snags.

Since I used Material, I thought I should put some special cosideration into how the site looks on Android. You can see I have a `theme-color` and `icon` specifically for Chrome on Android so the site will look lovely in your Lollipop multitasking screen with a coloured navigation bar.

## Code

I wrote the site as a single HTML file, with CSS and JS inline. For animations I used JS and jQuery alongside some CSS transitions. Dependancies aren't local so you can use it on it's own.

The biggest animation (the Material circle after loading) is a circular `<div>` which has its location reset to being exactly centred under the reload button based on a position tracker relative to the viewport. The circle then animates in size, opacity and colour to get the final effect, before resetting.

The weather data is from Yahoo Weather, and I used SimpleWeatherJS to make this easier.

## Feedback

You can [tweet me](http://twitter.com/gmph) or [email me](mailto:hi@grahammacphee.co.uk) if you have any questions about the project, or if you have any feedback.

## License

The project is licensed under the MIT License.
