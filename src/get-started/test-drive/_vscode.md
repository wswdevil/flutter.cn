<div class="tab-pane" id="vscode" role="tabpanel" aria-labelledby="vscode-tab" markdown="1">

## Create the app

  1. Start VS Code
  1. Invoke **View > Command Palette**
  1. Type "flutter", and select the **Flutter: New Project** action
  1. Enter a project name (such as `myapp`), and press **Enter**
  1. Create or select the parent directory for the new project folder
  1. Wait for project creation to complete and the `main.dart`
     file to appear

The command above creates a Flutter project directory called `myapp` that
contains a simple demo
app that uses [Material Components](https://material.io/guidelines).

In the project directory, the code for your app is in `lib/main.dart`.

## Run the app

 1. Locate the VS Code status bar (the blue bar at the bottom of the window)
 1. Select a device from the **Device Selector** area.
    For details, see [Quickly switching between Flutter devices][].
    - If no device is available and you'd like to use a device simulator,
      click **No Devices** and launch a simulator.
    - To setup a real device, follow the device-specific instructions on the
      [Get Started: Install](/get-started/install) page for your OS.
 1. Invoke **Debug > Start Debugging** or press <kbd>F5</kbd>.
 1. Wait for the app to launch &mdash; progress is printed
    in the **Debug Console** view.

{% capture save_changes -%}
  : invoke **File > Save All**,
  or click **Hot Reload** (the green circular arrow button)
{% endcapture %}

{% include_relative _try-hot-reload.md save_changes=save_changes %}

[Quickly switching between Flutter devices]: https://dartcode.org/docs/quickly-switching-between-flutter-devices

</div>