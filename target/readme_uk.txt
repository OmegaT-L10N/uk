@TRANSLATION_NOTICE@


Що таке OmegaT?
===============

OmegaT — це вільна програма з відкритим джерельним кодом, призначена для автоматизованого перекладу, що має серед іншого такі функції: робота з нечіткими збігами, пам’ять перекладів, пошук за ключовими словами, робота з глосаріями та використання попередніх перекладів при роботі з оновленими файлами оригіналу.



Інформація щодо ліцензування
=====================

OmegaT is available under the terms of the GNU General Public License as
published by the Free Software Foundation, either version 3 of the License, or
(at your option) any later version. Текст ліцензії подано у файлі
/docs/OmegaT-license.txt.

У програмі OmegaT використано кілька сторонніх бібліотек. У файлі /docs/OmegaT-license.txt названо ліцензії, відповідно до яких розповсюджується кожна бібліотека.



Prerequisites for installing OmegaT
===================================

OmegaT потребує оточення Java Runtime Environment (JRE) версії 1.8 чи вище,
яке повинно бути встановлено в системі.

Ми рекомендуємо використовувати пакунок OmegaT із включеним JRE, аби позбавити
Вас проблеми вибору, отримання та встановленням JRE.



Встановлення OmegaT (Windows)
===========================

Запустіть програму встановлення.



Встановлення OmegaT (Mac)
=======================

Unpack the OmegaT .zip archive to obtain a folder that contains a
documentation file and the OmegaT application. Move the folder to an
appropriate location such as the Applications folder.



Встановлення OmegaT (Linux)
=========================

Покладіть архів до будь-якої необхідної теки та розпакуйте його. OmegaT вже готова
до запуску.

Тим не менш, ви можете скористатися акуратнішим та більш дружнім до користувача
встановленням використавши скрипт (linux-install.sh). Для використання скрипту, відкрийте вікно терміналу (консоль), змініть теку
на ту, що містить OmegaT.jar та скрипт linux-install.sh, та
запустіть скрипт командою «./linux-install.sh».



Встановлення OmegaT (Solaris, FreeBSD, ...)
=========================================

Покладіть архів до будь-якої необхідної теки та розпакуйте його. OmegaT вже готова
до запуску.



Using Java Web Start for installing OmegaT (all platforms)
===========================================================

If you have already Java installed on your system, one way to install OmegaT
is to use Java Web Start.

For this purpose download the following file and then execute it:

   https://omegat.sourceforge.io/webstart/OmegaT.jnlp

It will install the correct environment for your computer and the application
itself on the first run. Later calls do not need to be online.



Launching OmegaT (Windows)
==========================

If, during installation, you have created a shortcut on the desktop, double-
click on that shortcut.

The install program can create shortcuts for you in the start menu, on the
desktop and in the quick launch area. You can also manually drag the file
OmegaT.exe to the start menu, the desktop or the quick launch area to link it
from there.

If you can see the file OmegaT but not OmegaT.exe in your File Manager
(Windows Explorer), change the settings so that file extensions are displayed.



Launching OmegaT (Mac)
======================

Double-click on the OmegaT application.

You may drag the OmegaT application to your dock or to the tool bar of a
Finder window to be able to launch it from any location. You can also launch
it from the Spotlight search field.



Launching OmegaT (Linux)
========================

If you used linux-install.sh script, you should be able to launch OmegaT with:

  Alt+F2

and then:

  omegat

For a more user-friendly way of launching OmegaT, you can use the Kaptain
script provided (omegat.kaptn). To use this script you must first install
Kaptain. You can then launch the Kaptain launch script with:

  Alt+F2

and then:

  omegat.kaptn



Launching OmegaT from the command line (all systems)
====================================================

The command to launch OmegaT is:

cd <folder where the file OmegaT.jar is located>

<name and path of the Java executable file> -jar OmegaT.jar

(The Java executable file is the file java on Linux and java.exe on Windows.
If Java is installed at system level and is in the command path, the full path
need not be entered.)



Contributors
============

OmegaT розроблена Кайт Годфрі.

Менеджер проекту OmegaT - Дідієр Бріль.

Previous contributors include:
(alphabetical order)

Contributions to the code are documented in /docs/contributors.txt.

Other contributions by
  Vincent Bidaux (documentation manager)
  Alex Buloichik (lead developer)
  Sabine Cretella
  Dmitri Gabinski
  Jean-Christophe Helary (localization manager)
  Aaron Madlon-Kay (integration manager)
  Samuel Murray
  Marc Prior (webmaster)
  and many, many more very helpful people

(If you think you have significantly contributed to the OmegaT Project but you
(don't see your name on the lists, feel free to contact us.)



Useful links
============

The most current info about OmegaT can be found at:

   http://www.omegat.org/

User support, at the Yahoo user group (multilingual), where the archives are
searchable without subscription:

   https://groups.yahoo.com/neo/groups/OmegaT/info

Requests for Enhancements (in English), at the SourceForge site:

   https://sourceforge.net/p/omegat/feature-requests/

Bug reports (in English), at the SourceForge site:

   https://sourceforge.net/p/omegat/bugs/
