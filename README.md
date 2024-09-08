# CurrentWeather
## Installation

To install this package, import 'https://github.com/diasyerlan/CurrentWeather' in SPM.

## Usage example

```swift

import UIKit
import CurrentCity

class ViewController: UIViewController {
    
    override func viewDidLoad() {
        super.viewDidLoad()

        // Initialize the LocationViewController
        let currentWeatherVC = WeatherViewController()

        // Add it as a child view controller
        addChild(currentWeatherVC)
        currentWeatherVC.view.frame = view.bounds
        view.addSubview(currentWeatherVC.view)
        currentWeatherVC.didMove(toParent: self)
    }
}

```
