## FastCopy

#### Deutsch
Dies ist die alte, kostenlose Version 4.x.x des Tools ["FastCopy"](https://fastcopy.jp/en/) von ["SHIROUZU Hiroaki"](https://github.com/shirouzu/), leicht ins Deutsche übersetzt mit einem moderneren Iconset und leicht geänderten Dialogdimensionen, um diese an die viel längeren Strings der deutschen Sprache anzupassen. Für die Übersetzung habe ich die englische Resourcen-Tabelle "1033" verwendet. Die deutsche Übersetzung ist im Detail nicht 100%-ig; ich habe nur das Hauptfenster und die String-Ressourcen übersetzt.

#### FastCopy ist großartig ...
- Es ist die schnellste Kopier-/Sicherungssoftware unter Windows.
- Es unterstützt UNICODE und grössere Dateipfadnamen-Längen als **MAX_PATH (260 Zeichen)**.
- **Sehr wichtig bei der Administration: es kopiert im Kommandozeilenmodus als GUI nahezu unsichtbar mit einem Icon in der Taskleiste, was für den/die Anwender/in ansprechender ist als ein Konsolen-Tool mit einem Konsolenfenster !**
- Es werden automatisch unterschiedliche Methoden ausgewählt, je nachdem ob sich "Quelle" und "Zielverzeichnis" auf derselben oder einer anderen Festplatte (oder SSD) befinden.
- Lesen und Schreiben von unterschiedlichen HDD wird jeweils parallel von separaten Threads verarbeitet.
- Von derselben HDD wird der Prozess verarbeitet, bis der große Puffer voll ist. Wenn der große Puffer gefüllt ist, wird der Schreibvorgang gestartet und in großen Mengen verarbeitet.
- Lese-/Schreibvorgänge werden ohne Betriebssystem-Cache verarbeitet, sodass andere Anwendungen nicht langsamer werden.
- Es kann eine Lese-/Schreibleistung erreicht werden, die nahe an der Gerätegrenze liegt.
- Einschluss-/Ausschlussfilter (UNIX-Wildcard-Stil) kann angegeben werden.
- Es kann ein relativer Pfad angegeben werden.
- Es läuft schnell und beansprucht keine Ressourcen, da kein "Windows-MFC" verwendet wird. **(Nur mit Win32-API und C-Laufzeit entwickelt)**
– In Version 3.0 oder höher wurde die INI Konfig-Datei von FastCopy von "FastCopy.ini" in **"FastCopy2.ini"** umbenannt.

#### English
This is the old, free version 4.x.x of the tool ["FastCopy"](https://fastcopy.jp/en/) by ["SHIROUZU Hiroaki"](https://github.com/shirouzu/), slightly translated into German with a more modern iconset and slightly changed dialog dimensions to fit the much longer strings of the German language. For the translation I used the English resource table "1033". The German translation is not 100% accurate in detail; i only translated the main window and string resources.

#### FastCopy is awesome ...
- It is the fastest Copy/Backup Software on Windows.
- It supports UNICODE and over **MAX_PATH (260 characters)** file pathname-lengths.
- **Very important for administration: it copies almost invisibly in command line mode as a GUI with an icon in the taskbar, which is more appealing to the user than a console tool with a console window !**
- It automatically selects different methods according to whether "Source" and "DestDir" are in the same or different HDD (or SSD).
- Diff HDD Reading and writing are processed respectively in parallel by separate threads.
- Same HDD Reading is processed until the big buffer fills. When the big buffer is filled, writing is started and processed in bulk.
- Reading/Writing are processed with no OS cache, so other applications do not become slow.
- It can achieve Reading/Writing performance that is close to the device limit.
- Include/Exclude Filter (UNIX Wildcard style) can be specified.
- Relative Path can be specified.
- It runs fast and does not hog resources, because "Windows-MFC" is not used. **(Designed using Win32 API and C Runtime only)**
- In Version 3.0 or later, FastCopy's INI settings-file has been renamed from "FastCopy.ini" to **"FastCopy2.ini"**.

I'm not the Developer of ["FastCopy"](https://fastcopy.jp/en/), the Copyright belongs to ["SHIROUZU Hiroaki"](https://github.com/shirouzu/):

#### License
```
FastCopy/FcHash/fcp ver4.x License

Copyright 2004-2023 SHIROUZU Hiroaki All rights reserved.
Copyright 2018-2023 FastCopy Lab, LLC. All rights reserved.

Redistributing and using this software, commercial or non-commercial,
is permitted if the following conditions are met:

1. Redistributions of this software must retain the above copyright
   notice, this list of conditions and the following disclaimer.

THIS SOFTWARE IS PROVIDED BY THE COPYRIGHT HOLDERS AND CONTRIBUTORS
"AS IS" AND ANY EXPRESS OR IMPLIED WARRANTIES, INCLUDING, BUT NOT
LIMITED TO, THE IMPLIED WARRANTIES OF MERCHANTABILITY AND FITNESS
FOR A PARTICULAR PURPOSE ARE DISCLAIMED. IN NO EVENT SHALL THE
COPYRIGHT OWNER OR CONTRIBUTORS BE LIABLE FOR ANY DIRECT, INDIRECT,
INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING,
BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES;
LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION) HOWEVER
CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT
LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN
ANY WAY OUT OF THE USE OF THIS SOFTWARE, EVEN IF ADVISED OF THE
POSSIBILITY OF SUCH DAMAGE.
```
