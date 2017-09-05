Example iOS projects that use https://github.com/levigroker/GRKOpenSSLFramework.


Solves https://github.com/levigroker/GRKOpenSSLFramework/pull/3#issuecomment-326637395


Podfiles have two options:


-  framework built by xcode9
  pod 'GRKOpenSSLFramework', :git => "https://github.com/vixentael/GRKOpenSSLFramework.git", :branch => 'patch-1'


-  framework built by xcode8
  pod 'GRKOpenSSLFramework', :git => "https://github.com/vixentael/GRKOpenSSLFramework.git", :branch => 'bitcode-xcode8'


Comment / uncomment line to use framework built by xcode8 or by xcode9.