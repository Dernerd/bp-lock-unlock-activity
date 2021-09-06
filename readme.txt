=== BuddyPress Lock Unlock Aktivitätivity ===
Contributors: DerN3rd
Tags: buddypress,activity,buddypress-activity
Requires at least: 4.5
Tested up to: 4.9.1
Stable tag: 1.0.6
Requires PHP: 5.3
License: GPLv2 or later
License URI: https://www.gnu.org/licenses/gpl-2.0.html

BuddyPress Lock Unlock Activity ermöglicht Benutzern das Schließen/Öffnen von Aktivitäten zum Kommentieren.

== Beschreibung ==

Das BuddyPress Lock Unlock-Aktivitäts-Plugin ermöglicht es Benutzern, ihre Aktivität zum Kommentieren zu sperren/zu öffnen. 
Ein Benutzer kann jede Aktivität als geschlossen markieren und niemand kann diese Aktivität kommentieren. 
Wenn der Benutzer die Aktivität erneut öffnet, steht sie erneut zum Kommentieren zur Verfügung. 
Es ist ein sehr kleines, einfaches Plugin ohne großartige Konfiguration. 
Es erlaubt einfach die Kommentarfunktion im Aktivitätsstream von dem jeweiligen Benutzer steuern zu lassen.

Es kann Flammenkriege in Deinem sozialen Netzwerk beenden und Deinen Benutzern das Gefühl geben, mehr Kontrolle über ihre Aktivitäten zu haben.

Features:

*   Aktivität kann gesperrt werden (bedeutet, dass kein neuer Kommentar zu dieser bestimmten Aktivität zulässig ist)
*   Aktivität kann entsperrt werden (Wenn eine gesperrte Aktivität entsperrt wird, können Benutzer dies erneut kommentieren)
*   Webseiten-Administrator kann jede Aktivität sperren, die er/sie möchte
*   Ein Benutzer kann seine eigenen Aktivitäten zum Kommentieren sperren/entsperren

Weitere Informationen findest Du auf der [Plugin-Seite von WMS N@W](https://n3rds.work/docs/buddypress-lock-unlock-aktivitaet-handbuch/)
== Installation ==

This section describes how to install the plugin and get it working.

e.g.

1. Upload the plugin files to the `/wp-content/plugins/bp-lock-unlock-activity` directory, or install the plugin through the WordPress plugins screen directly.
1. Activate the Lock Unlock Activity for BuddyPress through the 'Plugins' screen in WordPress
1. That's all. Visit the activity to see it in action.

== Frequently Asked Questions ==


== Changelog ==

= 1.0.6 =
* Added new filter to check user permission to lock and unlock activity.

= 1.0.5 =
* Fix translation of the button label.

= 1.0.4 =
* Separate class for open and close activity button

= 1.0.3 =
* Initial release on wp.org
* Ajaxified lock/unlock of activity.