# Enable-Airdrop-on-unsupported-macs
How to enable airdrop on an unsupported Mac

1. > Launch Terminal from /Applications/Utilities or via Spotlight.
2. >Enter the following command, and hit the “Enter” key:
      `defaults write com.apple.NetworkBrowser BrowseAllInterfaces 1`
3. >Enter the following command, and hit the “Enter” key:
      `killall Finder`
4. > Close the Terminal. If on a completely unsupported Mac, check that the Finder sidebar now shows an AirDrop entry, and open it. 

You should see this ![Screen Shot 2022-06-15 at 10 22 23 PM](https://user-images.githubusercontent.com/74008800/173942629-e17066f0-6335-4c83-8691-38b611075a23.jpg)

If at any point you wish to check the current status of the AirDrop hack, issue this command in Terminal:
`defaults read com.apple.NetworkBrowser`

Here a video 

https://user-images.githubusercontent.com/74008800/173955612-8b22e9f8-40cc-4042-8853-4e4091face26.mov

