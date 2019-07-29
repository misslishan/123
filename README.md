<!DOCTYPE html
	PUBLIC "-//W3C//DTD XHTML 1.0 Transitional//EN" "http://www.w3.org/TR/xhtml1/DTD/xhtml1-transitional.dtd">
<html xmlns="http://www.w3.org/1999/xhtml">

<head>
	<meta charset="utf-8" />
	<meta http-equiv="Content-Type" content="text/html; charset=gb2312" />
	<title>无标题文档</title>
	<style>
		.search-box {
			position: fixed;
			top: 1rem;
			left: 1rem;
			padding: .5rem;
			background: #ddd;
			opacity: .8;
		}
		.search-result {
			color: red;
		}
		#textvalue {
			margin-top: 4rem;
		}
	</style>
</head>

<body>
	<div class="search-box">
		<input type="text" id="searchvalue" />
		<input type="button" onclick="search()" value="搜索" />
		<input type="button" value="上一个" onclick="preOne()" />
		<input type="button" value="下一个" onclick="nextOne()" />
	</div>
	<div cols="100" rows="10" id="textvalue">安全生产技术试题
		<p id="1">1.设备使用安全管理制度不包括:</p>
			A.岗位责任制 B.操作证制度 C.安全检查、检验制度 D.生产许可证制度答案: D
			<p id="2">2.设备使用安全管理制度不包括:</p>
			A.维修保养制度 B.设计资格证制度 C.设备使用守则 D.交接班制度答案: B
			<p id="3">3.工人的培训教育一般分为_____三级。</p>
			A.厂、车间、班组 B.国家、省、市 C.省、市、县 D.省、县、企业答案: A
			<p id="4">4.安全检验是按一定的方法与检测技术对设备的安全性能进行____试验,以确定设备维修计划或安全运行年限。</p>
			A.预防性 B.危险性 C.疲劳性 D.稳定性答案: A
			<p id="5">5.接班人员必须提前______分钟到达现场,了解设备情况,认真接班并检查记录填写情况。</p>
			A.10~15 B.1~3 C.3~5 D.5~7 答案: A
			<p id="6">6.要求设备操作人员做到“三好”,其含义是:</p>
			A.管好、修好、养好 B.管好、用好、养好 C.修好、用好、管好 D.包好、管好、养好答案: B
			<p id="7">7.对设备操作人员做到“三好”中管好的要求不正确的是: </p>
			A.操作者对设备负有保管责任,未经领导同意,不许他人动用。 B.设备的附件、仪器、仪表、工具、安全防护装置必须保持完整无损。 C.设备运转时要离开岗位,应委托他人暂代管 D.设备发生事故,立即停车断电,保护现场,及时、真实地上报事故情况答案: C
			<p id="8">8.要求设备操作人员做到“四会”,其中不包括: </p>
			A.会改造 B.会排除故障 C.会使用 D.会检查答案: A
			<p id="9">9.操作工必须做到设备及其周围工作场地的四项要求中不包括: </p>
			A.整齐 B.宽敞 C.润滑 D.安全答案: B
			<p id="10">10.操作工必须做到设备及其周围工作场地的四项要求中不包括: </p>
			A.清洁 B.整齐 C.安全 D.宽敞答案: D
			<p id="11">11.要求设备操作人员做到“五项纪律”,其中不包括: </p>
			A.发生故障,立即排除或报告。 B.配戴防护手套 C.凭操作证使用设备,遵守安全操作规程。 D.随机附件、工具、文件齐全。答案: B
			<p id="12">12.要求设备操作人员要做到“润滑五定”,它们是: ______。 </p>
			A.定设备、定时、定质、定量、定人 B.定设备、定时、定油、定量、定人 C.定点、定时、定质、定量、定人 D.定设备、定时、定油、定工具、定人答案: C
			<p id="13">13.不属于设备操作人员要做到“润滑五定”内容的选项是: </p>
			A.定设备 B.定时 C.定质 D.定量答案: A
			<p id="14">14.在行车、龙门吊安全操作规程中,严禁吊物在人头上通过,吊运的物件离地不得超过____米高。 </p>
			A.2 B.2.5 C.1.5 D.1 答案: C
			<p id="15">15.按点检时间间隔和检查内容不同,点检可分为______三类。</p>
			A.定位点检、内部点检、专项点检 B.定位点检、移动点检、专项点检 C.定位点检、固定点检、专项点检 D.日常点检、定期点检、专项点检答案: D
			<p id="16">16.下列选项属于点检的是:</p>
			A.定位点检、 B.日常点检 C.内部点检 D.固定点检答案: B
			<p id="17">17.下列选项属于点检的是: A.固定点检 B.内部点检 C.专项点检 D.移动点检答案: C 18.操作工人(或专职点检人员)根据规定标准,以感官为主,每班对各设备关键部位进行技术状态和安全状况检查,并对设备进行必要的清扫、擦拭、润滑、紧固和调整,检查结果记入标准的点检表中。该项点检是:</p>
			A.日常点检 B.专项点检 C.定期点检 D.移动点检答案: A
			<p id="18">18.操作工人(或专职点检人员)根据规定标准,以感官为主,每班对各设备关键部位进行技术状态和安全状况检查,并对设备进行必要的清扫、擦拭、润滑、紧固和调整,检查结果记入标准的点检表中。该项点检是:</p>
			A.日常点检 B.专项点检 C.定期点检 D.移动点检答案: A
			<p id="19">19.由专职维修人员(包括技术人员)对某些特定的项目,如设备精度,某项或某功能参数等进行检查测定。该项点检是:</p> A.日常点检 B.专项点检 C.定期点检 D.移动点检答案: B
			<p id="20">20.由维修人员(或专职点检员)凭感官和专用检测工具,按一定时间周期对设备的技术状态和安全状况进行全面检查和测定。该项点检是: </p>
			A.日常点检 B.专项点检 C.定期点检 D.移动点检答案: C
			<p id="21">21.设备使用安全管理制度不包括: A.岗位责任制 B.操作证制度 C.安全检查、检验制度 D.生产许可证制度答案: D
			<p id="22">22.专项检查中的精密检查,是对设备的几何精度和加工精度有计划地定期进行检测,精度检查的目的是为____提供依据。</p>
			A.设备的调整、验收和报废更新 B.设备的调整、修理和报废更新 C.设备的调整、修理和验收 D.设备的调整、修理、验收和报废更新答案: D
			<p id="23">23.设备有害因素检测中不属于常见的检测项目的有</p>
			A.噪声检测 B.渗透检测 C.火灾的探测 D.电气设备的电气参数检测答案: B
			<p id="24">24.专项检查中的精密检查,是对设备的几何精度和加工精度有计划地定期进行检测,精度检查的目的是为____提供依据。</p>
			A.设备的调整和报废更新 B.设备的调整和修理 C.设备的调整、修理和验收 D.设备的调整、修理、验收和报废更新答案: D
				<p id="25">25.设备有害因素检测中不属于常见的检测项目的有</p> A.噪声检测 B.渗透检测 C.火灾的探测 D.电气设备的电气参数检测答案: B
				<p id="26">26.从系统诊断技术的内容来看,故障诊断专家系统的应用不包括</p>
				A.故障监测 B.故障分析 C.故障排除 D.决策处理答案: C
				<p id="27">27.设备有形磨损可分为三个阶段,第一阶段是初期磨损阶段,其</p>
				A.磨损速度缓慢 B.磨损速度快 C.磨损速度一般 D.磨损速度正常答案: B
				<p id="28">28.设备的偶发故障期处于:</p> A.新设备运转初期 B.正常运转期 C.设备运转后期 D.大修后投入使用初期答案: B
				<p id="29">29.从保证设备安全运行角度来说,更应强调的是:</p>
				A.预防性维修 B.事后维修 C.大修 D.改造维修答案: A
				<p id="30">30.不属于设备维护保养工作“三级保养制”的选项是:</p>
				A.日常保养 B.一级保养 C.二级保养 D.三级保养答案: D
				<p id="31">31.操作工人每班必须进行的设备保养工作是:</p>
				A.日常保养 B.一级保养 C.二级保养 D.专门保养答案: A
				<p id="32">32.以定期检查为主,辅以维护性检修的一种间接预防性维修形式是:</p>
				A.日常保养 B.一级保养 C.二级保养 D.专门保养答案: B
				<p id="33">33.以维持设备的技术状况为主的检修形式是:</p>
				A.日常保养 B.一级保养 C.二级保养 D.专门保养答案: C
				<p id="34">34.经组______后要求精度和性能达到工艺要求,无漏油、漏水、漏气、漏电现象,声响、震动、压力、温升等符合标准。</p>
				A.日常保养 B.一级保养 C.二级保养 D.专门保养答案: C
				<p id="35">35.二级保养以______为主实施。</p>
				A.专业维修人员 B.安全管理人员 C.操作人员 D.调度人员答案: A
				<p id="36">36.计划修理不包括的选项是:</p>
				A.小修 B.中修 C.大修 D.特别维修答案: D
				<p id="37">37.不符合设备检修结束后安全要求的选项是:</p>
				A.检查检修项目是否有遗漏 B.因检修需要而拆移的盖板、防护罩等安全设施应恢复正常 C.检修设备立即投入生产 D.对检修的设备进行单体和联动试车,验收交接,并做好记录答案: C
				<p id="38">38.进入设备内作业前,必须对设备内进行清洗和置换,使设备内空气质量达到安全要求。设备内空气氧含量不得低于_____。</p>
				A.38% B.8% C.28% D.18% 答案: D
				<p id="39">39.当对设备进行内检修作业时,设备内照明电压应不大于36V,在潮湿容器、狭小容器内作业应不大于_____V。</p>
				A.24 B.12 C.30 D.36 答案: B
				<p id="40">40.当对设备进行内检修作业时,设备内照明电压应不大于____V,在潮湿容器、狭小容器内作业应不大于12V。</p>
				A.24 B.12 C.30 D.36 答案: D
				<p id="41">41._______是设备管理的基础性工作,它为生产经营单位设备安全管理提供信息、资料和数据。</p>
				A.后勤管理 B.设备档案管理 C.人事档案管理 D.财务管理答案: B
				<p id="42">42.专项检查中的精密检查,是对设备的几何精度和加工精度有计划地定期进行检测,精度检查的目的是为____提供依据。</p>
				A.设备的调整、验收和报废更新 B.设备的调整、修理和报废更新 C.设备的调整、修理和验收 D.设备的调整、修理、验收和报废更新答案: D
				<p id="43">43.机械设备运行危区可按运动状态分为静止型危区、回转型危区、往复型危区和复合型危区,其中,属于静止型危区的是_______。</p>
				A.由平动或往复运动的机件形成 B.由复杂运动形成 C.由旋转物件形成 D.尖角、毛刺、带刃锋利的转动部分答案: A
				<p id="44">44.以下选项哪个符合金切机床应选装防护罩、盖或栏的规定?</p>
				A.距操作者站立地面高度≤3m处有外露的传动部位 B.旋转部位的键、销、楔等突出≥2mm 的部位 C.高于地面≥0.7m的操作平台或需巡视设备的平台 D.超出主轴后端30mm以上的工件答案: C
				<p id="45">45.金切机床在距操作者站立地面高度______处有外露的传动部位时,应装防护罩、盖、栏。</p>
				A.≤2m B.=2m C.≥2m D.=1.8m 答案: A
				<p id="46">46.金切机床旋转部位(机床本体或工件)的键、销、楔等突出______的部位,应装防护罩、盖、栏。</p>
				A.≤3 mm B.≥3mm C.≤3 mm D.=3 mm 答案: B
				<p id="47">47.高于地面______的操作平台或需巡视设备的平台,应装防护罩、盖、栏。</p>
				A.
				<0.7m B.≤0.7m C.≥0.7m D.≤0.5m 答案: C <p id="48">48.安装砂轮的法兰盘直径与砂轮直径的关系为:</p>
			A.
			<1/4~1/3 B.≥1/4~1/3 C.≤1/4 D.<1/3 答案: B <p id="49">49.机床保护接地线若明设,应选用:</p>
				A.
				<4mm2的铝芯线 B.不许使用铜芯线 C.≥4mm铝芯线 D.≥4mm2的铜芯线答案:D <p id="50">50.金切机床大刀架空程量</p>
					A.≤1/30转 B.>1/30转 C.>1/20转 D.<1/20转答案:A 
						<p id="51">51.金切机床小刀架空程量</p>
						A.>1/20转 B.≤1/20转 C.≥1/30转 D.>1/30转答案:B
						<p id="52">52.金切机床四方架压紧后手柄应处于:</p>
						A.第一象限的0~45? B.第一象限的45~90? C.第二象限的0~45? D.第二象限的45~90? 答案:A
						<p id="53">53.机床的电气箱柜门应关闭严密,门前______内无杂物、无工件,箱柜门开启方便</p>
						A.0.5m B.0.6m C.0.7m D.0.8m 答案: D
						<p id="54">54.机床局部或移动照明必须采用______安全电压</p>
						A.36V或24V B.36V或12V C.36V或6V D.24V或12V 答案: A
						<p id="55">55.机床使用220V整机照明灯高度应______(以操作站立面为准),线距规范,完好可靠,灯泡上部应装灯罩。</p>
						A.≥2.2m B.≥2.0m C.≥1.8m D.≥1.6m 答案: C
						<p id="56">56.不符合选购起重机械设备安全要求的选项是:</p>
						A.审查所选购设备的设计、制造单位是否合法、各类安全证书是否齐全 B.起重机械出厂时,必须附有起重机械安全技术监督检验合格证书 C.额定起重量符合要求,价格最低 D.必须购置有安全技术监督检验合格证书的产品答案: C
						<p id="57">57.起重机械使用运行检查不包括:</p>
						A.年度检查 B.每季检查 C.每月检查 D.每日检查答案: B
						<p id="58">58.在用起重机安全定期监督检验周期规定为①,电梯和载人升降机安全监督检验周期规定为②。</p>
						A.①一年②半年 B.①两年②一年 C.①三年②两年 D.①四年②三年答案: B
						<p id="59">59.起重机械的制造,必须先取得_____级安全技术部门的安全认可,安全认可每三年复审一次。</p>
						A.市 B.省 C.国家 D.县答案: B
						<p id="60">60.根据国家对起重机械的安全监察管理规定,安装修理起重机械的单位,必须先向所在地区的省级安全技术部门申请安全认可,并取得安全认可证书,安全认可证书有效期为_____。</p> A.四年 B.三年 C.二年 D.一年答案: B
						<p id="61">61.起重机钢丝绳的安全状况应______进行检查。</p>
						A.每年 B.每季 C.每月 D.每日答案: D
						<p id="62">62.起重机钢丝绳在一个捻节距内断丝数超过总丝数的______应该报废。</p>
						A.5% B.7% C.10% D.15% 答案: C
						<p id="63">63.机械设备运行危区可按运动状态分为静止型危区、回转型危区、往复型危区和复合型危区,其中,属于静止型危区的是_______。</p>
						A.由平动或往复运动的机件形成 B.由复杂运动形成 C.由旋转物件形成 D.尖角、毛刺、带刃锋利的转动部分答案: A
						<p id="64">64.起重机钢丝绳在一个捻节距内断丝数超过总丝数的10%应该______。</p>
						A.报废 B.正常使用 C.修复使用 D.进行负荷试验答案: A
						<p id="65">65.钢丝绳外层钢丝磨损量超过原直径的______ %应该报废。</p> A.50 B.40 C.30 D.20 答案: B
						<p id="66">66.吊运炽热金属或危险品的钢丝绳的断丝数达到一般起重设备钢丝绳的报废断丝数的______应该报废。</p> A.1/2 B.1/3 C.1/4 D.1/5 答案: A
						<p id="67">67.钢丝绳直径减小达____________应该报废。</p>
						A.5% B.7% C.10% D.15% 答案: B
						<p id="68">68.选用钢丝绳时,起升和变幅机构不得使用编结接长的钢丝绳,当需要接长钢丝绳时,必须保证接头连结强度不小于钢丝绳破断拉力的_____,且不得过滑轮入卷筒。</p>
						A.90% B.80% C.70% D.60% 答案: A
						<p id="69">69.吊钩负荷试验时,人力驱动的起升机构用吊钩,以______额定载荷作为检验载荷 A.1倍</p>
						B.1.2倍 C.1.5倍 D.2倍答案: C
						<p id="70">70.吊钩危险断面的高度磨损量达原尺寸的10%时,应</p>
						A.报废 B.堆焊修复 C.正常使用 D.进行负荷试验答案: A
						<p id="71">71.吊钩危险断面的高度磨损量达原尺寸的______时,应报废</p>
						A.15% B.10% C.8% D.5% 答案: B
						<p id="72">72.吊钩开口度比原尺寸增加15%,应</p>
						A.正常使用 B.修复 C.报废 D.留用观察答案: C
						<p id="73">73.吊钩开口度比原尺寸增加______时,应报废</p>
						A.5% B.8% C.10% D.15% 答案: D
						<p id="74">74.吊钩扭转变形超过5°时应</p> A.正常使用 B.修复 C.报废 D.进行负荷试验答案: A
						<p id="75">75.吊钩扭转变形量超过 ______时,应报废</p>
						A.10° B.9° C.8° D.7°答案: A
						<p id="76">76.起重机的环形链,链条工作时,与铅垂线之间夹角不应大于______</p>
						A.25° B.30° C.35° D.40°答案: B
						<p id="77">77.链环直径磨损达原直径的______时,应报废。</p>
						A.5% B.7% C.8% D.10% 答案: D
						<p id="78">78.链环直径磨损达原直径的10%时,应</p>
						A.报废 B.修复 C.正常使用 D.进行负荷试验答案: A
						<p id="79">79.链环直径磨损达原直径的5%时,应报废。</p>
						A.报废 B.修复 C.正常使用 D.进行负荷试验答案: C
						<p id="80">80.轮槽不均匀磨损达3mm时应</p>
						A.报废 B.修复 C.正常使用 D.进行负荷试验答案: A
						<p id="81">81.轮槽壁厚磨损达原壁厚的20%时应</p>
						A.报废 B.修复 C.正常使用 D.进行负荷试验答案: A
						<p id="82">82.轮槽壁厚磨损达原壁厚的10%</p> A.报废 B.修复 C.正常使用 D.进行负荷试验答案: C
						<p id="83">83.轮槽壁厚磨损达原壁厚的______应报废。</p>
						A.5% B.10% C.15% D.20% 答案: D
						<p id="84">84.起重机钢丝绳在一个捻节距内断丝数超过总丝数的10%应该______。</p>
						A.报废 B.正常使用 C.修复使用 D.进行负荷试验答案: A
	</div>

	<script>
		// String.prototype.replaceAll = function (s1, s2) {
		// 	return this.replace(new RegExp(s1, "gm"), s2);
		// }
		var resultNum = 0;

		function search() {
			var searchtext = document.getElementById("searchvalue").value;
			var textvalue = document.getElementById("textvalue").innerHTML;

			if (searchtext.length == 0) {
				return;
			}
			// document.getElementById("textvalue").innerHTML = textvalue.replaceAll(searchtext, 
			// 	"<font color='red' " + 'id="result' + ++resultCount + '">' +
			// 	searchtext + "</font>");
			document.getElementById('textvalue').innerHTML = textvalue.replace(new RegExp(searchtext, 'gm'),
				'<span class="search-result">' + searchtext + '</span>');
			var searchResults = document.getElementsByClassName('search-result');
			
			for (var i = 0; i < searchResults.length; i++) {
				searchResults[i].id = 'search-result-' + i;
			}
			locateResult(resultNum);
		}

		function locateResult(n) {
			location.hash = '#search-result-' + n;
		}

		function preOne() {
			locateResult(resultNum > 0 ? --resultNum : resultNum);
		}

		function nextOne() {
			locateResult(++resultNum);
		}
	</script>

</body>

</html>
