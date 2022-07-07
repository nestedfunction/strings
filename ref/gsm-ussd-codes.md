# GSM Unstructured Supplementary Service Data Codes
Source:(https://en.wikipedia.org/wiki/Unstructured_Supplementary_Service_Data)


<table>
    <caption>GSM USSD codes and their functions with various network operators
    </caption>
    <tbody>
        <tr>
            <th>Code</th>
            <th>Function</th>
            <th>Note</th>
            <th>Switch on</th>
            <th>Switch off</th>
            <th>Display status
            </th>
        </tr>
        <tr>
            <td>002
            </td>
            <td>all diversions
            </td>
            <td>unconditional, busy, unreachable, does not answer
            </td>
            <td>* * 002 * <b>number</b> * <b>BS</b> * <b>T</b> #
            </td>
            <td># # 002 * * <b>BS</b> #
            </td>
            <td>* # 002 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>004
            </td>
            <td>all conditional redirections
            </td>
            <td>busy, unreachable, does not answer
            </td>
            <td>* * 004 * <b>number</b> * <b>BS</b> * <b>T</b> #
            </td>
            <td># # 004 * * <b>BS</b> #
            </td>
            <td>* # 004 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>03
            </td>
            <td>Change Network password
            </td>
            <td>password is network dependent, default on some networks is 0000. See call barring functions *33
            </td>
            <td colspan="3">* * 03 * 330 * <b>old password</b> * <b>new password</b> * <b>new password</b> #
            </td>
        </tr>
        <tr>
            <td>04
            </td>
            <td>Change PIN</a>
            </td>
            <td>
            </td>
            <td colspan="3">* * 04 * <b>old PIN</b> * <b>new PIN</b> * <b>new PIN</b> #
            </td>
        </tr>
        <tr>
            <td>042
            </td>
            <td>Change PIN2
            </td>
            <td>Only with Phase 2 SIM
            </td>
            <td colspan="3">* * 042 * <b>old PIN2</b> * <b>new PIN2</b> * <b>new PIN2</b> #
            </td>
        </tr>
        <tr>
            <td>05
            </td>
            <td>Change PIN by PUK</a>
            </td>
            <td>
            </td>
            <td colspan="3">* * 05 * <b>PUK</b> * <b>new PIN</b> * <b>new PIN</b> #
            </td>
        </tr>
        <tr>
            <td>052
            </td>
            <td>Change PIN2 via PUK
            </td>
            <td>Only with Phase 2 SIM
            </td>
            <td colspan="3">* * 052 * <b>PUK</b> * <b>new PIN2</b> * <b>new PIN2</b> #
            </td>
        </tr>
        <tr>
            <td>06
            </td>
            <td>read device number (IMEI)
            </td>
            <td>
            </td>
            <td colspan="3">* # 06 #
            </td>
        </tr>
        <tr>
            <td>21
            </td>
            <td>unconditional divert
            </td>
            <td>all incoming calls will be diverted
            </td>
            <td>* * 21 * <b>number</b> * <b>BS</b> #
            </td>
            <td># # 21 * * <b>BS</b> #
            </td>
            <td>* # 21 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>30
            </td>
            <td>get the displayed (CLIP)
            </td>
            <td>as a callee get the CLIP displayed
            </td>
            <td>* 30 #
            </td>
            <td># 30 #
            </td>
            <td>* # 30 #
            </td>
        </tr>
        <tr>
            <td>31
            </td>
            <td>suppressing the transmission of caller's phone number (CLIR)
            </td>
            <td>for all subsequent calls
            </td>
            <td># 31 #
            </td>
            <td>* 31 #
            </td>
            <td>* # 31 #
            </td>
        </tr>
        <tr>
            <td>31
            </td>
            <td>temporary change of the transmission of CLIR
            </td>
            <td>valid just for the next call; no final #
            </td>
            <td># 31 # <b>number</b>
            </td>
            <td>* 31 # <b>number</b>
            </td>
            <td>
            </td>
        </tr>
        <tr>
            <td>330
            </td>
            <td>total incoming and outgoing service barring
            </td>
            <td>password is network dependent, default on some networks is 0000
            </td>
            <td>* 330 * <b>password</b> * <b>BS</b> #
            </td>
            <td># 330 * <b>password</b> * <b>BS</b> #
            </td>
            <td>* # 330 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>33
            </td>
            <td>outgoing call barring
            </td>
            <td>password is network dependent, default on some networks is 0000
            </td>
            <td>* 33 * <b>password</b> * <b>BS</b> #
            </td>
            <td># 33 * <b>password</b> * <b>BS</b> #
            </td>
            <td>* # 33 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>331
            </td>
            <td>outgoing international call barring
            </td>
            <td>password is network dependent, default on some networks is 0000
            </td>
            <td>* 331 * <b>password</b> * <b>BS</b> #
            </td>
            <td># 331 * <b>password</b> * <b>BS</b> #
            </td>
            <td>* # 331 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>332
            </td>
            <td>outgoing international call barring, excluding to home
            </td>
            <td>password is network dependent, default on some networks is 0000
            </td>
            <td>* 332 * <b>password</b> * <b>BS</b> #
            </td>
            <td># 332 * <b>password</b> * <b>BS</b> #
            </td>
            <td>* # 332 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>333
            </td>
            <td>total outgoing service barring
            </td>
            <td>password is network dependent, default on some networks is 0000
            </td>
            <td>* 333 * <b>password</b> * <b>BS</b> #
            </td>
            <td># 333 * <b>password</b> * <b>BS</b> #
            </td>
            <td>* # 333 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>35
            </td>
            <td>incoming call barring
            </td>
            <td>password is network dependent, default on some networks is 0000. Incompatible with call diversion
            </td>
            <td>* 35 * <b>password</b> * <b>BS</b> #
            </td>
            <td># 35 * <b>password</b> * <b>BS</b> #
            </td>
            <td>* # 35 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>351
            </td>
            <td>incoming call barring, when international roaming
            </td>
            <td>password is network dependent, default on some networks is 0000
            </td>
            <td>* 351 * <b>password</b> * <b>BS</b> #
            </td>
            <td># 351 * <b>password</b> * <b>BS</b> #
            </td>
            <td>* # 351 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>353
            </td>
            <td>total incoming service barring
            </td>
            <td>password is network dependent, default on some networks is 0000
            </td>
            <td>* 353 * <b>password</b> * <b>BS</b> #
            </td>
            <td># 353 * <b>password</b> * <b>BS</b> #
            </td>
            <td>* # 353 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>37
            </td>
            <td>Call back on busy (CCBS)
            </td>
            <td>valid on some mobile networks only
            </td>
            <td>* 37 #
            </td>
            <td># 37 #
            </td>
            <td>* # 37 #
            </td>
        </tr>
        <tr>
            <td>43
            </td>
            <td>incoming call notification when busy
            </td>
            <td>aka call waiting
            </td>
            <td>* 43 * <b>BS</b> #
            </td>
            <td># 43 * <b>BS</b> #
            </td>
            <td>* # 43 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>61
            </td>
            <td>call divert when not answered
            </td>
            <td>
            </td>
            <td>* * 61 * <b>number</b> * <b>BS</b> * <b>T</b> #
            </td>
            <td># # 61 * * <b>BS</b> #
            </td>
            <td>* # 61 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>62
            </td>
            <td>call divert when off or not reachable
            </td>
            <td>
            </td>
            <td>* * 62 * <b>number</b> * <b>BS</b> #
            </td>
            <td># # 62 * * <b>BS</b> #
            </td>
            <td>* # 62 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <td>67
            </td>
            <td>call divert when busy or pressing reject
            </td>
            <td>
            </td>
            <td>* * 67 * <b>number</b> * <b>BS</b> #
            </td>
            <td># # 67 * * <b>BS</b> #
            </td>
            <td>* # 67 * * <b>BS</b> #
            </td>
        </tr>
        <tr>
            <th>Code</th>
            <th>Function</th>
            <th>Note</th>
            <th>Switch on</th>
            <th>Switch off</th>
            <th>Display status
            </th>
        </tr>
    </tbody>
</table>