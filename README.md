Sessions To Watch From //build 2018
========================

Reflecting my own interests which might not align with yours - you might want to view a whole different bunch of sessions and I'll probably add a few more to this list once I've got through this lot.

Keynotes, I've seen these already
-------------------------------------------------

[Intelligent Cloud & Edge](https://channel9.msdn.com/Events/Build/2018/KEY01)

[Azure](https://channel9.msdn.com/Events/Build/2018/TK01)

[Microsoft 365](https://channel9.msdn.com/Events/Build/2018/TK02)

Breakout 75 Minutes
-----------------------

[Introducing ML.NET](https://channel9.msdn.com/Events/Build/2018/BRK3203)

[Cognitive Search](https://channel9.msdn.com/Events/Build/2018/BRK3201)

[Speech Services](https://channel9.msdn.com/Events/Build/2018/BRK3200)

[Windows IoT - Intelligent Edge and AI Platform](https://channel9.msdn.com/Events/Build/2018/BRK3806)

[Azure IoT Edge](https://channel9.msdn.com/Events/Build/2018/BRK3802)

[Azure Sphere](https://channel9.msdn.com/Events/Build/2018/BRK3801)

[Quantum and Q#](https://channel9.msdn.com/Events/Build/2018/BRK3601)

[Modernizing Desktop Apps](https://channel9.msdn.com/Events/Build/2018/BRK3501)

[Conversational AI, what's new?](https://channel9.msdn.com/Events/Build/2018/BRK3232)

[AI at Microsoft](https://channel9.msdn.com/Events/Build/2018/BRK3227)

[Bing Maps](https://channel9.msdn.com/Events/Build/2018/BRK3229)

[What's New with Azure Machine Learning](https://channel9.msdn.com/Events/Build/2018/BRK3226)

[Microsoft AI State of the Union](https://channel9.msdn.com/Events/Build/2018/BRK3224)

[Computer Vision for Developers](https://channel9.msdn.com/Events/Build/2018/BRK3222)

[Microsoft AI for Developers](https://channel9.msdn.com/Events/Build/2018/BRK3218)

[Demystifying Machine Learning](https://channel9.msdn.com/Events/Build/2018/BRK3215)

[AI + IoT](https://channel9.msdn.com/Events/Build/2018/BRK3205)

[Introduction to Blockchain](https://channel9.msdn.com/Events/Build/2018/BRK2507)

[MSIX Inside and Out](https://channel9.msdn.com/Events/Build/2018/BRK2432)

[PWA for Windows Devices](https://channel9.msdn.com/Events/Build/2018/BRK2428)

[C++/WinRT](https://channel9.msdn.com/Events/Build/2018/BRK2425)

[What's New for Windows UX Developers - Fluent and XAML](https://channel9.msdn.com/Events/Build/2018/BRK2423)

	XAML Control Gallery - updates are coming to it - > 75 samples now in this thing.
	End to end sample app - 'smart lighting'.
	Density - i.e. touch density versus mouse density.
		They've shrunk it down a little, you can also switch it to compact (template for 'compact')
	Depth - z translation and ThemeShadow. Translation is a Vector3(). Uses global lighting.
		building depth into all the popup type controls by default.
	Motion - done some work with connected animations, UIElements get natural motion
		can run composition animations on UI elements with certain properties.
		and implicit animations in XAML - change property, get animation.
	Color Schemes - makes it easy to brand the existing controls/regions.
	Reveal Interactions.
	Spatial audio on ElementSoundPlayer.

	NavigationView - added new modes (e.g. horizontal/top mode)
	Commanding - wanting to expose commands in multiple UX surfaces.
		A thing called UICommand that can then be used in resources & then re-used.
		Plus StandardUICommand - cut, copy, paste, etc.
	MenuBar control.
	CommandBarFlyout control.
	DropDownButton, SplitButton, ToggleSplitButton.
	DataGrid.
		Similar to the Silverlight DataGrid API.
	TreeView control.
	RichEditBox with @mentions & ContentLinks.

	x:Bind in Styles and ControlTemplates - can have function binding in templates
	can fire INotifyPropertyChange notifications for bindings to methods
	custom markup extensions present via IServiceProvider.

	Windows UI Library - NuGet package for the controls & styles.
	Same controls we use in Windows.
	
	Interop - WebView. Can provide responses to HTTP requests from the content.
		Also runs out of proc.
	XAML hosting in desktop apps (preview) or "XAML Islands".
		WPF/Windows Forms hosting of UWP.
	XAML Standard

	XamlDirect - dynamically generate UI with high perf (targeted at middleware).
	C++/WinRT support.

[Visual Studio and Xamarin](https://channel9.msdn.com/Events/Build/2018/BRK2422)

[Sets on Windows 10 and Your Phone](https://channel9.msdn.com/Events/Build/2018/BRK2417)

[Fluent Design: Evolution](https://channel9.msdn.com/Events/Build/2018/BRK2413)

[Developing for Sets on Windows 10](https://channel9.msdn.com/Events/Build/2018/BRK2412)

[The Future of C#](https://channel9.msdn.com/Events/Build/2018/BRK2155)

Talks about 7.1/7.2/7.3

	async main
	using default() without the type
	digit separators
	local functions
	better overload resolution
	selectively naming argumens to functions
	enum/delegate constraints on generic type parameters
	generic type parameters constrained to pointers (unsafe code)
		where T : unmanaged
	default naming of elements within tuples
	equality/non-equality of tuples
	
	talked about ref parameters
		extension methods can now take ref params
		in parameters - receiver can't change the value passed - read only ref
		ref returns - feels like this is giving C# the equivalent of C++ MyType& type passing around - pointer without a pointer.
		can also return ref readonly - all gets a bit nuanced.
		
Span<T> - feels like a pointer into a block of managed memory owned by (e.g.) an array or native memory etc. Can have read-only Spans. Can put Spans on the stack and have it own the memory (on the stack) with stackalloc keyword.

Then talked about new features...for 8

	compiler flag switches reference types to be non-nullable - e.g. string?
	'refactoring' of the switch statement
	property patterns
	deconstruction in patterns?
	System.Index
	async disposables - using await
	async enumerables

[.NET Overview and Roadmap](https://channel9.msdn.com/Events/Build/2018/BRK2100)

	Bit on Core 2.1, bit on Core 3.0, bit on VS features

Breakout 45 Minutes
-----------------------

[Cloud Based Game Development with Unity](https://channel9.msdn.com/Events/Build/2018/BRK3705)

[Mixed Reality Apps with New Windowing APIs](https://channel9.msdn.com/Events/Build/2018/BRK3506)

[Seizing the Mixed Reality Revolution](https://channel9.msdn.com/Events/Build/2018/BRK3504)

[Visual Layer in Fluent](https://channel9.msdn.com/Events/Build/2018/BRK3503)

[Windows 10 on ARM for Developers](https://channel9.msdn.com/Events/Build/2018/BRK2438)

[Pair Programming Made Awesome with Visual Studio Live Share](https://channel9.msdn.com/Events/Build/2018/BRK2130)

Pre-Record
-------------
[Project Rome in Microsoft Graph APIs](https://channel9.msdn.com/Events/Build/2018/THR5013)