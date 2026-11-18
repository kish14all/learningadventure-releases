# Learning Adventure - Pre-K through Grade 12 pilot

**Parent-supervised preview, not a reviewed or complete curriculum.** All lessons
and suggested curriculum mappings await educator review. Filters include All
curricula, Foundations, US, India, ICSE/ISC foundations and State-board foundations.
The last two currently use shared foundations, not individually mapped state
syllabi or verified ICSE/ISC coverage.
This download is not a Play Store or Microsoft Store release.

## Install

| Platform | Latest download | Installation |
| --- | --- | --- |
| Android | [LearningAdventure.apk](https://github.com/kish14all/learningadventure-releases/releases/latest/download/LearningAdventure.apk) | A grown-up downloads the APK, opens it, and approves Android installation. Android may require allowing installs from the browser. Review the publisher and source before approving. |
| Windows 10/11 x64 | [LearningAdventure-Windows.zip](https://github.com/kish14all/learningadventure-releases/releases/latest/download/LearningAdventure-Windows.zip) | Extract the **entire ZIP** into a folder, then run `learning_adventure.exe`. Do not run only the EXE from inside the ZIP. |

Scan this QR code on an Android phone to download the latest APK:

![Android installation QR](LearningAdventure-install-QR.png)

[Download the scalable QR image](LearningAdventure-install-QR.svg).

The QR contains the stable GitHub APK link above, not a third-party redirector.
Windows binaries are not Authenticode-signed; Windows may show a reputation warning.
Do not disable device protection or bypass a security detection. If your device or
administrator blocks installation, stop and ask them to review the download.

Each release includes `SHA256SUMS.txt` for checking downloaded files, the Android
signing certificate fingerprint and the corresponding private-source commit ID.
Checksums detect file changes; they are not independent publisher verification.

## Updates

In the app, open **Parent corner > App updates > Check for app updates**.
Parents can optionally enable a launch-time check, at most once a day. It is
**off by default**. Results appear in Parent corner, not during learning.

Update checks contact GitHub. GitHub receives ordinary network metadata, including
your IP address; learner progress is not uploaded. The parent must approve opening
the download. Android still requires installation approval. Keep the existing app
installed and install the new APK over it to retain local progress. Do not uninstall
the old app to update. Android updates must use the same signing key.

For Windows, close the app and extract the complete new ZIP into a new folder.
Run the new copy; files are not replaced automatically. The application identity
and local preference location remain the same.

## New lessons without reinstalling

Build 2 adds **Parent corner > Signed lesson updates > Check and download new
lessons**. The parent initiates each content check. Compatible lesson releases
download separately from the APK/Windows app and work offline after verification.
Updates are publisher-signed and checked before replacing the current library.
A failed transfer keeps the existing lessons. Parents can restore the previous
verified library when available, or use bundled lessons without deleting progress.
The initial online library can match the bundled version; this is normal, not a
missing download.
The expanded Pre-K-12 library requires app build 3 or later; install the new APK
over the existing app before downloading expanded content. A grades-3-5-only
cache cannot replace the expanded bundled library.

The separate public `learningadventure-content` repository hosts educational
content only. It never receives learning progress. GitHub receives ordinary network
metadata when a parent checks/downloads. Content signatures do not mean educator
approval; the library remains a draft.

## Build 5: students, recovery and a browsable library

Open app -> choose student -> **Continue learning** or start something new.
The illustrated home provides Learn, Practice, Play and solve, and My progress.
Grown-ups can add/edit/archive nickname/avatar profiles with age in years, school
grade and learning preferences. No full name or birth date is required.
Tap the avatar to switch; each child keeps separate marks, mistakes, preferences
and unfinished learning. Changing school grade preserves history.

Quiz/CogatMath recovery keeps exact questions, choices, answers and hints.
The optional CogatMath timer pauses in the background and checkpoints every second;
an abrupt termination can lose the subsecond remainder since its last checkpoint.
Lessons save their scroll-end/background/exit place; workshops save each action.
Starting something new asks before replacing the one unfinished activity.
Previous shared history is preserved for explicit assignment to one empty student,
not duplicated into siblings.

**Question library** exposes the bank in searchable/filterable 20-item pages,
including the complete 20,824-variation generated reasoning export across grades.
The 10/20/30-question session limit is not the library size. Hints, conceptual
clues and worked steps support practice; bank-launched practice is open-book.
Correct answers after help count as correct but do not raise challenge levels.

**Play and solve** includes five-round fraction, number-line, reading, density,
fictional-map and sentence workshops. Start reading currently has 12 original
short passages in four reading bands, not thousands of reading passages or a
validated assessment. Start math uses topic-adaptive generated practice.
Workshop models are foundations, not complete courses for every grade.
Discoveries, optional celebrations, reflection and parent insights encourage
growth without punitive streaks or public rankings. School grade, challenge level
and practice marks are separate; none is an official CogAT score.

**Parent corner > Manage students and backups** exports/restores all students,
including archived profiles and unassigned history. Restore previews the backup
and requires confirmation before replacing all local student records.
Backups are checksummed plaintext, not encrypted/authenticated: save privately and
clear the clipboard afterward. Progress is local; there is no cloud sync.
Content reports are saved locally for parent review/export, not sent automatically.

## Pilot features and privacy

Build 4 introduced **CogatMath**, now available from Home/Practice: original offline number analogies,
number puzzles and number series for every app level. Pre-K is readiness play,
not an official CogAT test level. These are generated practice variations, not
official test items, endorsed preparation or standardized scores.
Three consecutive independent correct answers increase the next challenge; two consecutive
wrong answers decrease it. Progress is saved separately per student/grade.
The optional timer is off by default and pauses in the background. Below 10
seconds the countdown turns red; after expiry the child can still answer.
There is no extra timeout penalty. Results show late correct and late wrong
answers separately. Other CogAT-style batteries are not included.
The development export has 20,824 distinct generated practice variations,
separate from the general lesson bank below. The app creates variations locally;
this is not 20,824 independently authored or reviewed concepts, and no separate
fixed mock-test bank is included.

Math, science, social studies and English; concepts, examples, FAQ, quick questions,
quizzes, generated math, explanations, saved questions and local progress.
Build 3 covers all 14 levels from Pre-K and Kindergarten through Grade 12.
Grades 11-12 have math, physics, chemistry, biology and English.
Early activities include local pictures and tap-to-listen with an installed
offline English device voice. No audio plays automatically and no microphone
is used. If a voice is unavailable, install an offline voice in device speech
settings or read together with a grown-up. Online-only voices are not used.
Build 2 adds balanced quizzes, recent-question avoidance, adaptive challenge levels,
spaced reviews and weekly discoveries. Generated/structured variants are not
independently authored or reviewed lessons. Difficulty labels reflect practice
history, not a standardized assessment.

The offline library has **438 draft topics** with concepts, examples and FAQ, and
**8,280 bank questions**: 84 authored pilot questions, 6,210 structured tasks and
1,986 generated math items. Every new grade/subject combination includes six
topics and 102-108 questions; the original grades 3-5 questions are preserved.
Runtime math provides additional numerical variations. The larger development
export is not the number of independent
teaching concepts.

Learning works offline. There are no ads, analytics, child accounts, open chat,
purchases or cloud progress sync. Optional network actions and their implications
are described in Parent corner. The arithmetic parent checkpoint is a convenience,
not security, age verification or legal parental consent. Device storage loss or
uninstalling can delete progress.

Source is maintained separately in the owner's **private** `learningadventure-app`
repository. This public repository contains download information, QR files and
release binaries only; no source access or open-source license is implied.
Real-device Android installation and usability still require parent testing.
