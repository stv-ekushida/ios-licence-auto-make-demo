# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'ios-licence-auto-make-demo' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
  pod 'Alamofire', '~> 4.2'
  pod 'ObjectMapper', '~> 2.2'

  # Pods for ios-licence-auto-make-demo

  target 'ios-licence-auto-make-demoTests' do
    inherit! :search_paths
    # Pods for testing
  end

end

post_install do | installer |
require 'fileutils'
FileUtils.cp_r('Pods/Target Support Files/Pods-ios-licence-auto-make-demo/Pods-ios-licence-auto-make-demo-Acknowledgements.plist', 'ios-licence-auto-make-demo/Settings.bundle/Acknowledgements.plist', :remove_destination => true)
end
