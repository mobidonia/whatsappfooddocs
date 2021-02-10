# Localization and Time format

## Localization

By default is set in English but you can change it on some of the available languages.

This option you will find in **Settings &gt; Localization**.

![](../.gitbook/assets/screenshot.png)

### **Adding new language**

Since some of the languages are still not available you can add manually new language. There are several steps you need to do for achieving that using **Translation plugin** available with the admin account.

Open the translation plugin located in the side menu under name **Translations**.

When the translations page will be opened select the **Languages** menu from the navigation.

Click on the **Add** button and enter the **language name/locale** and save it. 

Now you will able to see all the words and sentences that you will need to translate it manually.

## Time Format

From the version 1.2 there is option for customizing the time format in the script for working hours.

There are two options:

* 24 hours time format `24hours`
* AM PM format `AM/PM`

By default is 24 hours time format.

```text
TIME_FORMAT="24hours"
```

## Time zone

To set the correct timezone that your site operates in create .env variable.

It is really important to have done this step, in order restaurant closing and open time to work ok.

```text
TIME_ZONE=UTC
```

List of available [timezones](https://www.php.net/manual/en/timezones.php).

