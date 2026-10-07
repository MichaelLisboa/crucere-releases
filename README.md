<p align="center">
  <img src="assets/banner.svg" alt="Crucere" width="100%">
</p>

<p align="center">
  <a href="https://github.com/MichaelLisboa/crucere-releases/releases/download/v0.5.19/Crucere-0.5.19-windows.exe"><img src="assets/windows.svg" alt="Download for Windows" width="102"></a>
  <a href="https://github.com/MichaelLisboa/crucere-releases/releases/download/v0.5.19/Crucere-0.5.19-mac.pkg"><img src="assets/mac.svg" alt="Download for Mac" width="72"></a>
  <a href="https://github.com/MichaelLisboa/crucere-releases/releases/download/v0.5.19/Crucere-0.5.19-android.apk"><img src="assets/android.svg" alt="Download for Android" width="96"></a>
</p>

# You collected the research. Crucere reads it.

Be honest. That folder of PDFs, reports and spreadsheets? You haven't read it.

Nobody has. So, hand it over.

A room of five AI researchers reads every source. They show you where your sources agree, where they collide, and which ones never mention the thing at all. They suggest the questions worth asking. Then they argue it out, and a Judge rules on what was actually said.

You get the answer, the reasoning behind it, and a report you can hand to someone else. PDF, PowerPoint, audio or video. (The phone doesn't make the PDF yet.)

And all of it runs on your own computer. Nothing you upload or ask goes anywhere. No account. No sign-in. No cloud.

## Get it

| | Download | Runs on | Size |
| --- | --- | --- | --- |
| **Windows** | [Crucere-0.5.19-windows.exe](https://github.com/MichaelLisboa/crucere-releases/releases/download/v0.5.19/Crucere-0.5.19-windows.exe) | Windows 10 or 11, 64-bit | 1.7 GB |
| **Mac** | [Crucere-0.5.19-mac.pkg](https://github.com/MichaelLisboa/crucere-releases/releases/download/v0.5.19/Crucere-0.5.19-mac.pkg) | Apple silicon | 382 MB |
| **Android** | [Crucere-0.5.19-android.apk](https://github.com/MichaelLisboa/crucere-releases/releases/download/v0.5.19/Crucere-0.5.19-android.apk) | Android 12 or later | 133 MB |

This is version 0.5.19, and it's an alpha. Things will break.

## Yes, the Windows one is huge

1.7 GB. I know.

Crucere needs something to run the AI models. On Windows and Mac that something is [Ollama](https://ollama.com), a free program, and both installers bring it along. Ollama for Windows carries support for a lot of different graphics cards, so it's big. Ollama for Mac isn't. That's the whole difference between 1.7 GB and 382 MB.

Already have Ollama? The installer leaves yours alone.

Android doesn't use Ollama at all. It runs its own model, Google's Gemma, built to run directly on a phone.

## Your computer will complain

The installers aren't signed yet, so your device will ask if you're sure. You're sure.

- **Windows.** Run the file. If you see "Windows protected your PC", choose **More info**, then **Run anyway**.
- **Mac.** Right-click the file and choose **Open**. Still refusing? Go to **System Settings → Privacy & Security** and choose **Open Anyway**.
- **Android.** Open the file, and let your browser or file manager install apps when it asks.

## One more download

Sorry. Crucere fetches its AI model the first time it opens: about 2.5 GB on Windows and Mac, about 2.7 GB on Android.

Go make a coffee. After that, it works without an internet connection.

## Something broke?

Good. That's what an alpha is for.

[Open an issue](https://github.com/MichaelLisboa/crucere-releases/issues) and tell me what happened. Questions, revelations and insults are all welcome.

Thanks for trying it.
