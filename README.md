# Implement-ORB-SLAM-Algorithm-and-Mapping-by-ROS

<br>

## Location: 
- NCKU DAA(Department of Aeronautics and Astronautics)

<br>

## Camera Calibration Parameter
<table>
    <tr>
        <td width="20%" height="100%">
            <table>
                <tr>
                    <td align="center"><center>Parameter</center></td>
                    <td align="center"><center>Value</td>
                </center></tr>
                <tr>
                    <td align="right">Camera.fx </td>
                    <td align="left">639.361574</td>
                </tr>
                <tr>
                    <td align="right">Camera.fy </td>
                    <td align="left">647.470474</td>
                </tr>
                <tr>
                    <td align="right">Camera.cx</td>
                    <td align="left">290.001610</td>
                </tr>
                <tr>
                    <td align="right">Camera.cy</td>
                    <td align="left">175.213520</td>
                </tr>
                <tr>
                    <td align="right">Camera.k1</td>
                    <td align="left">-0.044398</td>
                </tr>
                <tr>
                    <td align="right">Camera.k2</td>
                    <td align="left">0.149793</td>
                </tr>
                <tr>
                    <td align="right">Camera.p1</td>
                    <td align="left">-0.035826</td>
                </tr>
                <tr>
                    <td align="right">Camera.p2</td>
                    <td align="left">0.002884</td>
                </tr>
            </table>
        </td>
        <td width="50%" height="100%">
            <center>
            <img src="https://github.com/Zong-Xi/Implement-ORB-SLAM-Algorithm-and-Mapping-by-ROS/blob/main/picture/camera/calibration.png" width="70%" alt="pict" />
            </center>
        </td>
    </tr>
</table>

<br>

## SLAM Result without Camera Calibration 

<table>
    <center>
    <tr>
        <td><center>Loop Closing Fail 1</center></td>
        <td><center>Loop Closing Fail 2</center></td>
    </tr>
    </center>
    <tr>
        <td align="center"><img src="https://github.com/Zong-Xi/Implement-ORB-SLAM-Algorithm-and-Mapping-by-ROS/blob/main/picture/without-calibration/fail1.png" ></td>
        <td align="center"><img src="https://github.com/Zong-Xi/Implement-ORB-SLAM-Algorithm-and-Mapping-by-ROS/blob/main/picture/without-calibration/fail2.png" ></td>
    </tr>
</table>

<br>


## SLAM Result with camera Calibration

<table>
    <tr>
        <td><center>corner 1</center></td>
        <td><center>corner 2</center></td>
    </tr>
    <tr>
        <td align="center"><img src="https://github.com/Zong-Xi/Implement-ORB-SLAM-Algorithm-and-Mapping-by-ROS/blob/main/picture/with-calibration/corner1.png" ></td>
        <td align="center"><img src="https://github.com/Zong-Xi/Implement-ORB-SLAM-Algorithm-and-Mapping-by-ROS/blob/main/picture/with-calibration/corner2.png" ></td>
    </tr>
    <tr>
        <td><center>Before Loop Closing</center></td>
        <td><center>After Loop Closing</center></td>
    </tr>
    <tr>
        <td align="center"><img src="https://github.com/Zong-Xi/Implement-ORB-SLAM-Algorithm-and-Mapping-by-ROS/blob/main/picture/with-calibration/before-loop-closing.png" ></td>
        <td align="center"><img src="https://github.com/Zong-Xi/Implement-ORB-SLAM-Algorithm-and-Mapping-by-ROS/blob/main/picture/with-calibration/after-loop-closing.png" ></td>
    </tr>
</table>
