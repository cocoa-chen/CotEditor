source 'https://github.com/CocoaPods/Specs.git'

platform :osx, '10.10'
workspace 'CotEditor'


abstract_target 'app' do
    project 'CotEditor/CotEditor'

    pod 'NSHash'
    pod 'WFColorCode'


    target 'CotEditor'
    target 'CotEditor -AppStore'
end


target 'Tests' do
    project 'CotEditor/CotEditor'

    pod 'WFColorCode'
end
