#Syntax 
# Action Menu View

One Paragraph of project description goes here

## Getting Started

ActionMenuView is a series of menu options shown as a View. This offers as action buttons some top-level options while pouring over the remaining options as elements in a menu overload. It allows applications to display inline packages of behaviour with similar or repeated content.

### History

It was introduce to the Android System 21. It is included in the AndroidX library.

### Major Attributes and Methods

Attributes
```
Inherited XML attributes
android.widget.LinearLayout
android.view.ViewGroup
android.view.View
```

And Methods

```
public void dismissPopupMenus ()
public ActionMenuView.LayoutParams generateLayoutParams (AttributeSet attrs)
public Menu getMenu ()
public Drawable getOverflowIcon ()
public int getPopupTheme ()
public boolean hideOverflowMenu ()
public boolean isOverflowMenuShowing ()
public void onConfigurationChanged (Configuration newConfig)
public void onDetachedFromWindow ()
public void setOnMenuItemClickListener (ActionMenuView.OnMenuItemClickListener listener)
public void setOverflowIcon (Drawable icon)
public void setPopupTheme (int resId)
public boolean showOverflowMenu ()
protected boolean checkLayoutParams (ViewGroup.LayoutParams p)
protected ActionMenuView.LayoutParams generateDefaultLayoutParams ()
protected ActionMenuView.LayoutParams generateLayoutParams (ViewGroup.LayoutParams p)
protected void onLayout (boolean changed, 
                int left, 
                int top, 
                int right, 
                int bottom)
protected void onMeasure (int widthMeasureSpec, 
                int heightMeasureSpec)
```

End with an example of getting some data out of the system or using it for a little demo

## Running the tests

Explain how to run the automated tests for this system

### Break down into end to end tests

Explain what these tests test and why

```
Give an example
```

### And coding style tests

Explain what these tests test and why

```
Give an example
```

## Deployment

Add additional notes about how to deploy this on a live system

## Built With

* [Dropwizard](http://www.dropwizard.io/1.0.2/docs/) - The web framework used
* [Maven](https://maven.apache.org/) - Dependency Management
* [ROME](https://rometools.github.io/rome/) - Used to generate RSS Feeds

## Contributing

Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 

## Authors

* **Billie Thompson** - *Initial work* - [PurpleBooth](https://github.com/PurpleBooth)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details

## Acknowledgments

* Hat tip to anyone whose code was used
* Inspiration
* etc
