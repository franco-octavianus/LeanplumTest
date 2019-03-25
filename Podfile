# Uncomment the next line to define a global platform for your project
platform :ios, '9.3'

use_frameworks!

abstract_target 'Main' do
  # Can't build to device using Leanplum 2.3.1 
  pod 'Leanplum-iOS-SDK', '2.4.0'
  
  # Leanplum 2.0.6 can build to device
#  pod 'Leanplum-iOS-SDK', '2.0.6
  
  pod 'Moya'
  
  target 'LeanplumTest'
end
