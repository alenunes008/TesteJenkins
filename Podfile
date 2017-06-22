# Uncomment the next line to define a global platform for your project
# platform :ios, '9.0'

target 'ProjetoJenkins' do
  # Comment the next line if you're not using Swift and don't want to use dynamic frameworks
  use_frameworks!
    # Pods for AVCol
    pod 'Alamofire', '4.3.0'
    pod 'Fabric', '1.6.11'
    pod 'Crashlytics', '3.8.4'
    #pod 'Koloda', '4.0'
    pod 'pop', '1.0.9'
    
    pod 'EVReflection', '4.4.1'
    pod 'IDZSwiftCommonCrypto', '0.9.1'
    pod 'DynamicBlurView', '1.3.0'
    pod 'GoogleTagManager', '3.15.2'

  # Pods for ProjetoJenkins

  target 'ProjetoJenkinsTests' do
    inherit! :search_paths
    # Pods for testing
    # Pods for AVCol
    pod 'Alamofire', '4.3.0'
    pod 'Fabric', '1.6.11'
    pod 'Crashlytics', '3.8.4'
    #pod 'Koloda', '4.0'
    pod 'pop', '1.0.9'
    
    pod 'EVReflection', '4.4.1'
    pod 'IDZSwiftCommonCrypto', '0.9.1'
    pod 'DynamicBlurView', '1.3.0'
    pod 'GoogleTagManager', '3.15.2'

  end

end

post_install do |installer|
    installer.pods_project.targets.each do |target|
        target.build_configurations.each do |config|
            config.build_settings['EXPANDED_CODE_SIGN_IDENTITY'] = ""
            config.build_settings['CODE_SIGNING_REQUIRED'] = "NO"
            config.build_settings['CODE_SIGNING_ALLOWED'] = "NO"
        end
    end
end

