platform :ios, '9.0'

target 'Grow 7' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!

  # Pods for Grow 7
  pod 'Charts'
  pod 'SVProgressHUD', :git => 'https://github.com/SVProgressHUD/SVProgressHUD.git'
  pod 'Alamofire'
  pod 'SwiftyJSON'
  pod 'Firebase'
  pod 'Firebase/Auth'
  pod 'Firebase/Database'

end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['CLANG_WARN_DOCUMENTATION_COMMENTS'] = 'NO'
        end
    end
end
