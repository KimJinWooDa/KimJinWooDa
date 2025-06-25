<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=00AAFF&height=200&section=header&text=김진우&fontSize=60&animation=fadeIn&fontColor=ffffff&fontAlignY=38&desc=Unity%20Developer&descAlignY=55&descSize=20" width="100%"/>
</div>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&weight=600&size=28&pause=1000&color=00A8FC&center=true&vCenter=true&random=false&width=600&lines=안녕하세요!+👋;유니티+개발자입니다+🎮;VR+전문가입니다+🥽;게임+제작을+사랑합니다+💚" />
</div>

<div align="center">
  <a href="https://unity.com/">
    <img src="https://img.shields.io/badge/Unity-%23000000.svg?style=for-the-badge&logo=unity&logoColor=white"/>
  </a>
  <a href="https://docs.microsoft.com/dotnet/csharp/">
    <img src="https://img.shields.io/badge/C%23-%23239120.svg?style=for-the-badge&logo=c-sharp&logoColor=white"/>
  </a>
  <a href="https://visualstudio.microsoft.com/">
    <img src="https://img.shields.io/badge/Visual_Studio-%235C2D91.svg?style=for-the-badge&logo=visual-studio&logoColor=white"/>
  </a>
  <a href="https://git-scm.com/">
    <img src="https://img.shields.io/badge/Git-%23F05033.svg?style=for-the-badge&logo=git&logoColor=white"/>
  </a>
  <a href="https://www.oculus.com/">
    <img src="https://img.shields.io/badge/Oculus-1C1E20?style=for-the-badge&logo=oculus&logoColor=white"/>
  </a>
</div>

<br>

<!-- 개발자 소개 -->
<div align="center">
  <h2>💻 개발자 소개</h2>
</div>

```csharp
using UnityEngine;

public class Developer : MonoBehaviour
{
    [Header("개인 정보")]
    [SerializeField] private string 이름 = "김진우";
    [SerializeField] private int 나이 = 26;
    [SerializeField] private string[] 전문분야 =
    { 
        "Unity3D", "C# 프로그래밍", 
        "VR/AR 개발", "게임 최적화" 
    };

    [Header("열정")]
    [Range(0, 100)] public float 창의성 = 95f;
    [Range(0, 100)] public float 문제해결력 = 92f;
    [Range(0, 100)] public float 팀워크 = 88f;

    private void Awake() => 
        Debug.Log("열정적인 유니티 개발자가 깃허브에 접속했습니다!");
    
    private void Start() => CreateAmazingGames();
    
    private void CreateAmazingGames()
    {
        while(true)
        { 
            LearnNewSkills(); 
            BuildAwesomeProjects(); 
            ShareKnowledge();
            // 무한 반복!
        }
    }
}
```

<h2 align="center">🎯 전문 분야</h2>

<div align="center">
<table>
  <tr>
    <td align="center" width="33%">
      <img src="https://cdn-icons-png.flaticon.com/512/5360/5360804.png" width="60" height="60"><br>
      <b>Unity 엔진 마스터리</b>
      <br><br>
      <img src="https://img.shields.io/badge/URP-00AAFF?style=flat-square"/>
      <img src="https://img.shields.io/badge/Shader_Graph-FF4400?style=flat-square"/>
      <img src="https://img.shields.io/badge/Timeline-22AA44?style=flat-square"/>
      <br>
      <i>최신 렌더링 파이프라인부터<br>고급 에디터 확장까지</i>
    </td>
    <td align="center" width="33%">
      <img src="https://cdn-icons-png.flaticon.com/512/8028/8028314.png" width="60" height="60"><br>
      <b>2D/3D 게임 시스템 설계</b>
      <br><br>
      <img src="https://img.shields.io/badge/컴포넌트_기반_아키텍처-FF6B6B?style=flat-square"/>
      <img src="https://img.shields.io/badge/상태_머신-48CFAD?style=flat-square"/>
      <img src="https://img.shields.io/badge/디자인_패턴-AC92EC?style=flat-square"/>
      <br>
      <i>최적화된 게임플레이 메커니즘과<br>확장 가능한 시스템 설계</i>
    </td>
    <td align="center" width="33%">
      <img src="https://cdn-icons-png.flaticon.com/512/6897/6897039.png" width="60" height="60"><br>
      <b>물리 기반 시뮬레이션</b>
      <br><br>
      <img src="https://img.shields.io/badge/Rigidbody-4FC1E9?style=flat-square"/>
      <img src="https://img.shields.io/badge/Collider_최적화-FFCE54?style=flat-square"/>
      <img src="https://img.shields.io/badge/사실적_물리-FC6E51?style=flat-square"/>
      <br>
      <i>자연스러운 움직임과<br>물리 시스템 구현</i>
    </td>
  </tr>
  <tr>
    <td align="center" width="33%">
      <img src="https://cdn-icons-png.flaticon.com/512/2920/2920349.png" width="60" height="60"><br>
      <b>모바일 & 성능 최적화</b>
      <br><br>
      <img src="https://img.shields.io/badge/메모리_관리-ED5565?style=flat-square"/>
      <img src="https://img.shields.io/badge/프로파일링-5D9CEC?style=flat-square"/>
      <img src="https://img.shields.io/badge/배터리_효율-A0D468?style=flat-square"/>
      <br>
      <i>72+ FPS의 쾌적한 성능과<br>최적의 리소스 활용</i>
    </td>
    <td align="center" width="33%">
      <img src="https://cdn-icons-png.flaticon.com/512/8638/8638426.png" width="60" height="60"><br>
      <b>VR 애플리케이션</b>
      <br><br>
      <img src="https://img.shields.io/badge/Oculus-5D9CEC?style=flat-square"/>
      <img src="https://img.shields.io/badge/OpenXR-AC92EC?style=flat-square"/>
      <br>
      <i>몰입형 경험과<br>직관적 인터랙션 설계</i>
    </td>
    <td align="center" width="33%">
      <img src="https://cdn-icons-png.flaticon.com/512/1998/1998342.png" width="60" height="60"><br>
      <b>AI & 머신 러닝</b>
      <br><br>
      <img src="https://img.shields.io/badge/게임_AI-5E72E4?style=flat-square"/>
      <img src="https://img.shields.io/badge/ML--Agents-FF5483?style=flat-square"/>
      <img src="https://img.shields.io/badge/강화학습-26DE81?style=flat-square"/>
      <br>
      <i>지능적 NPC와<br>적응형 게임 시스템</i>
    </td>
  </tr>
</table>
</div>

<br>

<!-- 지렁이 애니메이션 -->
<div align="center">
  <img src="https://raw.githubusercontent.com/platane/snk/output/github-contribution-grid-snake-dark.svg" width="100%" />
</div>

<br>

<h2 align="center">📬 연락처</h2>

<!-- 명함 스타일의 연락처 -->
<div align="center">
  <table>
    <tr>
      <td align="center" bgcolor="#222" style="border-radius:15px; padding:25px;">
        <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/unity/unity-original.svg" width="60" height="60"/>
        <h3 style="color:white; margin:10px 0;">김진우</h3>
        <p style="color:#AAA; font-size:16px;">Unity 게임 개발자 | XR 전문가 | AI 응용</p>
        <div style="margin:20px 0;">
          <a href="mailto:wlsdn62290@gmail.com">
            <img src="https://img.shields.io/badge/이메일-wlsdn62290@gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"/>
          </a>
        </div>
        <div>
          <a href="https://wlsdn629.tistory.com/">
            <img src="https://img.shields.io/badge/개발_블로그-wlsdn629.tistory.com-orange?style=for-the-badge&logo=blogger&logoColor=white" alt="Blog"/>
          </a>
        </div>
      </td>
    </tr>
  </table>
</div>

<br>

<!-- 푸터 -->
<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=28&duration=3000&pause=1000&color=00AAFF&center=true&multiline=true&random=false&width=600&height=80&lines=Unity+%7C+Game+Creator+%7C+XR+Expert;%F0%9F%8E%AE+Unity%EB%A1%9C+%EC%84%B8%EC%83%81%EC%9D%84+%EB%B3%80%ED%99%94%EC%8B%9C%ED%82%A4%EB%8A%94+%EA%B0%9C%EB%B0%9C%EC%9E%90+%F0%9F%8E%AE" alt="Typing SVG" />
  
  <!-- 세련된 푸터 -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=2,3,12,19,20,22&height=120&section=footer&fontSize=70&animation=fadeIn" width="100%" />
</div>
