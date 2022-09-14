# Advanced MS-Paint App

Has extended capabilities beyond the MS Paint App included with Windows. Has the ability to save files.

## Written in C#

Code originally supplied by malharthi in August, 2012:

https://github.com/malharthi/Paint

Code has been updated from Visual Studio 2010 SP1 to be compatible with newer VS 2022 and .Net 4.

## Uses .Net 4.0

Visual Studio code has been updated from 2012 to 2022.

### Compatible with Visual Studio 2022.

09/14/2022: While importing Visual Studio 2022 made non-functional changes to this project in order to enable the project to open in released versions of Visual Studio newer than Visual Studio 2010 SP1 without impacting project behavior.

Program.cs:

```

using System;
using System.Diagnostics;
using System.Collections.Generic;
using System.Windows.Forms;

namespace Paint
{
    static class Program
    {
        [STAThread]
        static void Main()
        {
            Application.EnableVisualStyles();
            Application.SetCompatibleTextRenderingDefault(false);
            Application.Run(new PaintForm());
        }
    }
}
```
