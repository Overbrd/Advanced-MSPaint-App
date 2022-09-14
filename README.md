###Advanced MS-Paint App

##Written in C#.

##Uses .Net 4.0.

#Compatible with Visual Studio 2022.

Code originally supplied by malharthi in August, 2012:

https://github.com/malharthi/Paint

Code has been updated to be compatible with newer VS and .Net 4.

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
