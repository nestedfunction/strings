# Calling Number Display Codes (Telstra & Optus networks)
Source: (https://www.accesscomms.com.au/ref_codes/)



<h2>Fixed-line telephones</h2>
<table summary="Calling Number Display Codes">
    <thead>
        <tr>
            <th scope="row">Feature</th>
            <th scope="row">Activate</th>
            <th scope="row">Use</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>CND blocking prefix</td>
            <td><strong>1831 + </strong><em>phone number</em></td>
            <td>Used to block outgoing CND info for a single call on a line that is preset to automatically send CND information.</td>
        </tr>
        <tr>
            <td>CND sending prefix</td>
            <td><strong>1832 +</strong><em>phone number</em></td>
            <td>Used to send outgoing CND info for a single call on a line that is preset not to automatically send CND information.</td>
        </tr>
    </tbody>
</table>
<h2>Mobile telephones</h2>
<table summary="Network Feature codes">
    <thead>
        <tr>
            <th scope="row">Feature</th>
            <th scope="row">Activate</th>
            <th scope="row">Use</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>CND blocking prefix</td>
            <td><strong>#31# + </strong><em>phone number</em></td>
            <td>Used to block outgoing CND info for a single call on a mobile that is preset to automatically send CND information.</td>
        </tr>
        <tr>
            <td>CND sending prefix</td>
            <td><strong>*31# +</strong><em>phone number</em></td>
            <td>Used to send outgoing CND info for a single call on a mobile that is preset not to automatically send CND information.</td>
        </tr>
    </tbody>
</table>
<p><a name="telstra"></a></p>
<h2>Telstra Network Feature Codes</h2>
<p>Legend FAT = Feature Access Tone RVA = Recorded Voice Announcement PIN = Personal Identification Number AXE = Ericsson Exchange S12 = Alcatel Exchange</p>
<p>"Easycall" and "Faxstream Duet" are registered trademarks of Telstra Corporation Limited</p>
<table summary="Telstra Network Feature codes">
    <thead>
        <tr>
            <th scope="row">Feature</th>
            <th scope="row">Activate</th>
            <th scope="row">Cancel</th>
            <th scope="row">Variables (Time/PIN or Numbers)</th>
            <th scope="row">Status</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Last Number Redial (AXE Only)</td>
            <td>0 #</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Call Return</td>
            <td>* 10 #</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Multiple Number - Second Line Number</td>
            <td>* 11 * 2 #</td>
            <td>&nbsp;</td>
            <td>* 11 * 2 # (2nd dial tone) * 21 phone number #</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Faxstream Duet - Second Line Number</td>
            <td>* 11 * 3 #</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Call Forwarding Timed</td>
            <td>* 16 # (RVA)</td>
            <td># 16 # (RVA)</td>
            <td>* 87&nbsp; PIN * (RVA) 9 * (RVA) ?</td>
            <td>* # 16 # (RVA)</td>
        </tr>
        <tr>
            <td>Call Forwarding Immediate &nbsp;- Variable</td>
            <td>* 21 phone number #</td>
            <td># 21 #</td>
            <td>&nbsp;</td>
            <td>* # 21 # (RVA)</td>
        </tr>
        <tr>
            <td>Call Forwarding Immediate - Fixed</td>
            <td>* 21 #</td>
            <td># 21 #</td>
            <td>&nbsp;</td>
            <td>* # 21 # (RVA)</td>
        </tr>
        <tr>
            <td>Call Forwarding on Busy - Variable</td>
            <td>* 24 phone number #</td>
            <td># 24 #</td>
            <td>&nbsp;</td>
            <td>* # 24 # (RVA)</td>
        </tr>
        <tr>
            <td>Call Forwarding on Busy - Fixed</td>
            <td>* 25 #</td>
            <td># 25 #</td>
            <td>&nbsp;</td>
            <td>* # 25 # (RVA)</td>
        </tr>
        <tr>
            <td>Password Control</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>* 30&nbsp; old PIN * new PIN * new PIN # (RVA)</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>CND blocking per call (mobile phone)</td>
            <td># 31 # phone number</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>Check "phone/settings" menu.</td>
        </tr>
        <tr>
            <td>CND sending per call (mobile phone)</td>
            <td>*31# phone number</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>Check "phone/settings" menu.</td>
        </tr>
        <tr>
            <td>CND blocking per call (fixed-line phone)</td>
            <td>1831 phone number</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>* # 1831 # (RVA)</td>
        </tr>
        <tr>
            <td>CND sending per call (fixed-line phone)</td>
            <td>1832 phone number</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>* # 1831 # (RVA)</td>
        </tr>
        <tr>
            <td>Call Control - Predefined</td>
            <td>* 33 PIN #</td>
            <td># 33 PIN #</td>
            <td>&nbsp;</td>
            <td>* # 33 # (RVA)</td>
        </tr>
        <tr>
            <td>Auto Call Back</td>
            <td>Recall * 37 # (RVA)</td>
            <td># 37 # (RVA)</td>
            <td>&nbsp;</td>
            <td>* # 37 # (RVA)</td>
        </tr>
        <tr>
            <td>Call Waiting</td>
            <td>* 43 # (FAT)</td>
            <td># 43 # (FAT)</td>
            <td>&nbsp;</td>
            <td>* # 43 # (RVA)</td>
        </tr>
        <tr>
            <td>Call Waiting over-ride per call (AXE Only)</td>
            <td>* 44 phone number</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Abbreviated Dialling Individual and Group</td>
            <td>* 51 abv code number #</td>
            <td># 51 abv code #</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Delayed Hotline</td>
            <td>* 53 hot line number #</td>
            <td># 53 #</td>
            <td>&nbsp;</td>
            <td>* # 53 # (RVA)</td>
        </tr>
        <tr>
            <td>Call Forwarding on No Answer - Variable</td>
            <td>* 61 phone number #</td>
            <td># 61 #</td>
            <td>* 61 phone number * time in secs #</td>
            <td>* # 61 # (RVA)</td>
        </tr>
        <tr>
            <td>Call Forwarding on No Answer - Fixed</td>
            <td>* 62 #</td>
            <td># 62 #</td>
            <td>* 62 * time in secs #</td>
            <td>* # 62 # (RVA)</td>
        </tr>
        <tr>
            <td>Include Line in Hunt Group</td>
            <td>* 76 #</td>
            <td># 76 #</td>
            <td>&nbsp;</td>
            <td>*#76 # (RVA)</td>
        </tr>
        <tr>
            <td>Changing Redirect List for Selective Call Forwarding</td>
            <td>&nbsp;</td>
            <td>&nbsp;</td>
            <td>* 87 PIN * (RVA) 4 * (RVA) ?</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Smart (Selective) Ring</td>
            <td>* 88 # (RVA)</td>
            <td># 88 # (RVA)</td>
            <td>* 87 PIN * (RVA) ? * (RVA) ?</td>
            <td>* # 88 # (RVA)</td>
        </tr>
        <tr>
            <td>Selective Call Forwarding</td>
            <td>* 92 # (RVA)</td>
            <td># 92 # (RVA)</td>
            <td>&nbsp;</td>
            <td>* # 92 # (RVA)</td>
        </tr>
    </tbody>
</table>
<h2><a name="optus"></a>Optus Network Feature Codes</h2>
<p>Legend FAT = Feature Access Tone RVA = Recorded Voice Announcement PIN = Personal Identification Number DMS = Nortel DMS100 Exchange</p>
<table summary="Optus Network Feature codes">
    <thead>
        <tr>
            <th scope="row">Feature</th>
            <th scope="row">Activate</th>
            <th scope="row">Cancel</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>CND Blocking Prefix</td>
            <td>*31 (FAT) phone number</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>CND Sending Prefix</td>
            <td>*32 (FAT) phone number</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Selective Call Reject</td>
            <td>*60</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Selective Call Divert</td>
            <td>*63</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Selective Call Accept</td>
            <td>*68</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Call Return</td>
            <td>* 69</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Call Divert</td>
            <td>* 78 (FAT)<em>phone number</em></td>
            <td># 78 (FAT)</td>
        </tr>
        <tr>
            <td>Call Waiting</td>
            <td>&nbsp;</td>
            <td># 87</td>
        </tr>
        <tr>
            <td>VoiceMail Access</td>
            <td>* 96</td>
            <td>&nbsp;</td>
        </tr>
        <tr>
            <td>Speed Dial</td>
            <td>* 99 <em>abbrev code number</em> <strong>#</strong></td>
            <td>&nbsp;</td>
        </tr>
    </tbody>
</table>

