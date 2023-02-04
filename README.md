# Python-Error-faced
A git repository for past python errors and solutions would contain documentation, explanations, and solutions for python errors I were encountered in the past, it could be organized by date. It could be used as a reference for future development and troubleshooting.

<br>

<table id="customers">
  <tr>
    <td>Number</td>
    <td>Error</td>
    <td>Answer</td>
  </tr>
  
  <tr>
    <td>1</td>
    <td>Error in pydub
    <br>
    FileNotFoundError: [WinError 2] The system cannot find the file specified
    </td>
    <td>Install ffmpeg<br>
    for anaconda "conda install -c conda-forge ffmpeg"
    and add "AudioSegment.ffmpeg = "/absolute/path/to/ffmpeg"" this line after import pydub
    </td>
  </tr>
  
  <tr>
    <td>1</td>
    <td>Error in raspberrypi
    <br>
    "error: can not find Rust Compiler"<br>
    "ERROR: Failed building wheel for tokenizers"
    </td>
    <td>Just because I am using 32 bit raspberrypi OS<br>
    when I switch to 64 error sol automatically
    </td>
  </tr>
  
  <tr>
    <td>1</td>
    <td>Error in raspberrypi
    <br>
    RaspberryPI not starting in putty 
    </td>
    <td>
    for this error enable ssh using other monitar<br> 
    Write "sudo raspi-config" and then enable SSH
    </td>
  </tr>
  
  <tr>
    <td>1</td>
    <td>Error in raspberrypi
    <br>
    vnc viewer screen is not fit to screen 
    </td>
    <td>"vncserver -geometry 1600x1200 -randr 1600x1200,1440x900,1024x768"
    <br> run above command in putty
    </td>
  </tr>
  
</table>
