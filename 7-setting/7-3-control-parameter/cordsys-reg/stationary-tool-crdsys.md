# 7.3.6.2 정치툴 좌표계

로봇 툴은 로봇 선단에 부착된 툴입니다. 일반적으로 로봇은 로봇에 부착된 툴을 이용하여 작업을 수행합니다. 대표적인 것으로 아크 용접이 있습니다. 아크 용접 툴은 통상적으로 로봇 선단에 부착되며 외부에 고정되어 있는 작업물에 용접을 수행할 때 사용합니다.

이에 반해서 정치툴\(Stationary Tool\)은 작업하는 툴이 로봇이 아닌 외부에 부착되어 있는 것으로, 이 경우에는 로봇이 작업물을 핸들링하여 외부에 고정된 툴에 위치시킴으로써 작업을 수행하게 됩니다. 정치툴을 이용한 대표적인 작업은 실링 작업입니다. 통상적으로 실링 작업은 외부에 부착된 툴이 실링에 필요한 용제를 일정한 양으로 토출하면 로봇이 작업물을 들고 실링에 필요한 궤적을 생성하여 작업합니다.



![&#xADF8;&#xB9BC; 58 &#xC2E4;&#xB9C1; &#xC791;&#xC5C5; &#xC608;](../../../.gitbook/assets/image%20%28124%29.png)

이 궤적을 생성하기 위해 로봇은 자체에 부착된 툴이 아닌 외부에 부착된 툴을 기준으로 직선 \(L\) 및 원호 \(C\) 보간을 수행합니다. 이때 정치툴 보간 기능을 사용합니다.

정치툴 보간 기능을 이용하면 로봇이 취부한 작업물의 자세가 변경되어도 정치툴의 작업물 상의 이동 경로는 직선 및 원호를 유지할 수 있습니다. 이와 같이 외부 툴의 이동 경로가 중요한 작업에는 반드시 정치툴 보간 기능을 이용합니다.

정치툴 보간 기능을 이용하려면 정치툴 좌표계를 반드시 설정해야 합니다.



정치툴 좌표계를 설정하는 방법은 다음과 같습니다.

1.	\[2: 제어 파라미터 &gt; 6: 좌표계 등록 &gt; 2: 정치툴 좌표계\] 메뉴를 터치하십시오.

2.	원하는 탭을 선택하고 정치툴 좌표계의 위치를 등록하십시오.

![](../../../.gitbook/assets/image%20%28179%29.png)



<table>
  <thead>
    <tr>
      <th style="text-align:left">&#xBC88;&#xD638;</th>
      <th style="text-align:left">&#xC124;&#xBA85;</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td style="text-align:left">
        <img src="../../../.gitbook/assets/c1.png" alt/>
      </td>
      <td style="text-align:left">&#xC815;&#xCE58;&#xD234; &#xC88C;&#xD45C;&#xACC4;&#xB294; &#xD0ED;&#xC744;
        &#xC120;&#xD0DD;&#xD558;&#xC5EC; &#xCD1D; 4 &#xAC1C;(tool 0 ~ tool 3)&#xB97C;
        &#xC124;&#xC815;&#xD560; &#xC218; &#xC788;&#xC2B5;&#xB2C8;&#xB2E4;.</td>
    </tr>
    <tr>
      <td style="text-align:left">
        <img src="../../../.gitbook/assets/c2.png" alt/>
      </td>
      <td style="text-align:left">
        <ul>
          <li>[OK]: &#xBCC0;&#xACBD; &#xB0B4;&#xC6A9;&#xC744; &#xC800;&#xC7A5;&#xD569;&#xB2C8;&#xB2E4;.</li>
          <li>[&#xC790;&#xB3D9;&#xC124;&#xC815;]: &#xD604;&#xC7AC;&#xC758; TCP &#xC704;&#xCE58;&#xB97C;
            &#xC815;&#xCE58;&#xD234; &#xC88C;&#xD45C;&#xACC4;&#xC758; &#xC704;&#xCE58;&#xB85C;
            &#xC124;&#xC815;&#xD569;&#xB2C8;&#xB2E4;.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>
