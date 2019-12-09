
# Action Menu View

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
protected void onLayout (boolean changed, int left, int top, int right, int bottom)
protected void onMeasure (int widthMeasureSpec, int heightMeasureSpec)
```

## Project Upload

Here is the link for my sample [project](https://github.com/junedacaya/ActionMenuViewTutorial)
I added a simple TODO list for easy code creation guide

### References
[FOSSASSIA](https://blog.fossasia.org/adding-actionmenuview-to-place-navigation-buttons-in-phimpme-android/)

[ANDROID STUDIO](https://developer.android.com/reference/android/widget/ActionMenuView)

[STACKOVERFLOW](https://stackoverflow.com/questions/27988346/how-to-use-actionmenuview)


