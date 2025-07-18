<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Contact Card</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#165DFF',
                        whatsapp: '#25D366',
                        wechat: '#07C160',
                        facebook: '#1877F2',
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                }
            }
        }
    </script>
    <style type="text/tailwindcss">
        @layer utilities {
            .content-auto {
                content-visibility: auto;
            }
            .card-shadow {
                box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.1), 0 8px 10px -6px rgba(0, 0, 0, 0.1);
            }
            .transition-smooth {
                transition: all 0.3s ease;
            }
            .rtl {
                direction: rtl;
            }
            .rtl-icon {
                transform: scaleX(-1);
            }
        }
    </style>
</head>
<body class="bg-gray-50 min-h-screen flex items-center justify-center p-4">
    <div id="contact-card" class="bg-white rounded-2xl card-shadow w-full max-w-md overflow-hidden">
        <!-- 头部区域 -->
        <div class="bg-gradient-to-r from-primary to-blue-400 p-6 text-white">
            <h1 class="text-[clamp(1.5rem,3vw,2rem)] font-bold mb-2" data-i18n="title">Contact Me</h1>
            <p class="text-white/80" data-i18n="subtitle">Connect with me instantly</p>
        </div>
        
        <!-- 联系列表 -->
        <div class="p-6 space-y-4">
            <!-- WhatsApp -->
            <a href="#" id="whatsapp-link" class="flex items-center justify-between p-4 rounded-xl bg-whatsapp/10 hover:bg-whatsapp/20 transition-smooth">
                <div class="flex items-center">
                    <i class="fa fa-whatsapp text-whatsapp text-2xl mr-4"></i>
                    <span class="text-gray-800 font-medium text-lg" data-i18n="whatsapp">WhatsApp</span>
                </div>
                <i class="fa fa-arrow-right text-gray-400 rtl-icon"></i>
            </a>
            
            <!-- 微信 -->
            <a href="#" id="wechat-link" class="flex items-center justify-between p-4 rounded-xl bg-wechat/10 hover:bg-wechat/20 transition-smooth">
                <div class="flex items-center">
                    <i class="fa fa-weixin text-wechat text-2xl mr-4"></i>
                    <span class="text-gray-800 font-medium text-lg" data-i18n="wechat">WeChat</span>
                </div>
                <i class="fa fa-arrow-right text-gray-400 rtl-icon"></i>
            </a>
            
            <!-- Facebook -->
            <a href="#" id="facebook-link" class="flex items-center justify-between p-4 rounded-xl bg-facebook/10 hover:bg-facebook/20 transition-smooth">
                <div class="flex items-center">
                    <i class="fa fa-facebook-official text-facebook text-2xl mr-4"></i>
                    <span class="text-gray-800 font-medium text-lg" data-i18n="facebook">Facebook</span>
                </div>
                <i class="fa fa-arrow-right text-gray-400 rtl-icon"></i>
            </a>
        </div>
        
        <!-- 底部 -->
        <div class="px-6 py-4 bg-gray-50 text-center text-gray-500 text-sm">
            <p data-i18n="factory-info">From Chinese lithium battery factory, get product catalog and quote</p>
        </div>
    </div>

    <script>
        // 语言包配置
        const translations = {
            'en-US': {
                title: 'Contact Me',
                subtitle: 'Connect with me instantly',
                whatsapp: 'WhatsApp',
                wechat: 'WeChat',
                facebook: 'Facebook',
                'factory-info': 'From Chinese lithium battery factory, get product catalog and quote'
            },
            'zh-CN': {
                title: '联系我',
                subtitle: '立即与我取得联系',
                whatsapp: 'WhatsApp',
                wechat: '微信',
                facebook: 'Facebook',
                'factory-info': '来自中国锂电池工厂，获取产品目录和报价'
            },
            'ar-SA': {
                title: 'اتصل بي',
                subtitle: 'تواصل معي على الفور',
                whatsapp: 'واتساب',
                wechat: 'ويتشات',
                facebook: 'فيسبوك',
                'factory-info': 'من مصنع بطاريات الليثيوم الصيني، احصل على كتالوج المنتجات وعرض سعر'
            },
            'de-DE': {
                title: 'Kontaktiere mich',
                subtitle: 'Komme sofort mit mir in Kontakt',
                whatsapp: 'WhatsApp',
                wechat: 'WeChat',
                facebook: 'Facebook',
                'factory-info': 'Von chinesischer Lithium-Batterie-Fabrik, Produktkatalog und Angebot erhalten'
            },
            'ru-RU': {
                title: 'Свяжитесь со мной',
                subtitle: 'Свяжитесь со мной мгновенно',
                whatsapp: 'WhatsApp',
                wechat: 'ВейЧат',
                facebook: 'Фейсбук',
                'factory-info': 'От китайской фабрики литиевых батарей. Получить каталог продукции и коммерческое предложение'
            }
        };

        // 检测用户语言并应用翻译
        function detectAndApplyLanguage() {
            const userLang = navigator.language || navigator.userLanguage;
            const defaultLang = 'en-US';
            
            // 查找最匹配的语言
            let matchedLang = defaultLang;
            for (const lang in translations) {
                if (userLang === lang || userLang.startsWith(lang.split('-')[0])) {
                    matchedLang = lang;
                    break;
                }
            }
            
            // 应用翻译
            const elements = document.querySelectorAll('[data-i18n]');
            elements.forEach(el => {
                const key = el.getAttribute('data-i18n');
                if (translations[matchedLang][key]) {
                    el.textContent = translations[matchedLang][key];
                }
            });
            
            // 特殊处理：阿拉伯语需要从右到左显示
            if (matchedLang === 'ar-SA') {
                document.body.classList.add('rtl');
                document.getElementById('contact-card').classList.add('text-right');
                // 反转箭头图标
                document.querySelectorAll('.rtl-icon').forEach(icon => {
                    icon.classList.add('transform', 'scale-x-[-1]');
                });
            } else {
                // 确保非RTL语言不应用RTL样式
                document.body.classList.remove('rtl');
                document.getElementById('contact-card').classList.remove('text-right');
            }
        }

        // 初始化链接跳转逻辑
        function initLinks() {
            const phoneNumber = '8618938295136';
            const facebookId = '100085046826505';
            
            // WhatsApp链接
            document.getElementById('whatsapp-link').addEventListener('click', function(e) {
                e.preventDefault();
                try {
                    // 检测设备类型
                    const isMobile = /iPhone|iPad|iPod|Android/i.test(navigator.userAgent);
                    
                    if (isMobile) {
                        // 移动设备尝试打开WhatsApp应用
                        window.location.href = `whatsapp://send?phone=${phoneNumber}`;
                        
                        // 设置超时，如果2秒内没有跳转，则打开网页版
                        setTimeout(() => {
                            window.location.href = `https://api.whatsapp.com/send?phone=${phoneNumber}`;
                        }, 2000);
                    } else {
                        // 桌面设备直接打开网页版
                        window.location.href = `https://web.whatsapp.com/send?phone=${phoneNumber}`;
                    }
                } catch (error) {
                    // 出错时打开网页版
                    window.location.href = `https://api.whatsapp.com/send?phone=${phoneNumber}`;
                }
            });
            
            // 微信链接
            document.getElementById('wechat-link').addEventListener('click', function(e) {
                e.preventDefault();
                try {
                    // 微信跳转逻辑
                    const isMobile = /iPhone|iPad|iPod|Android/i.test(navigator.userAgent);
                    const isWechat = /MicroMessenger/i.test(navigator.userAgent);
                    
                    if (isWechat) {
                        // 如果已经在微信内，提示用户复制号码
                        alert('请手动复制号码添加：' + phoneNumber);
                        navigator.clipboard.writeText(phoneNumber).then(() => {
                            alert('号码已复制到剪贴板');
                        });
                    } else if (isMobile) {
                        // 非微信环境，提示用户在微信中打开
                        alert('请在微信中搜索此号码添加：' + phoneNumber);
                    } else {
                        // 桌面设备
                        alert('请在手机微信中搜索此号码添加：' + phoneNumber);
                    }
                } catch (error) {
                    alert('无法自动跳转微信，请手动添加：' + phoneNumber);
                }
            });
            
            // Facebook链接
            document.getElementById('facebook-link').addEventListener('click', function(e) {
                e.preventDefault();
                try {
                    const isMobile = /iPhone|iPad|iPod|Android/i.test(navigator.userAgent);
                    
                    if (isMobile) {
                        // 检测iOS或Android
                        if (/iPhone|iPad|iPod/i.test(navigator.userAgent)) {
                            // iOS设备
                            window.location.href = `fb://profile/${facebookId}`;
                        } else {
                            // Android设备
                            window.location.href = `fb://page/${facebookId}`;
                        }
                        
                        // 设置超时，如果2秒内没有跳转，则打开网页版
                        setTimeout(() => {
                            window.location.href = `https://www.facebook.com/profile.php?id=${facebookId}`;
                        }, 2000);
                    } else {
                        // 桌面设备直接打开网页版
                        window.location.href = `https://www.facebook.com/profile.php?id=${facebookId}`;
                    }
                } catch (error) {
                    // 出错时打开网页版
                    window.location.href = `https://www.facebook.com/profile.php?id=${facebookId}`;
                }
            });
        }

        // 页面加载完成后初始化
        document.addEventListener('DOMContentLoaded', function() {
            detectAndApplyLanguage();
            initLinks();
        });
    </script>
</body>
</html>    
