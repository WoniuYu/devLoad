JWT 使用jwt制定的规则可以生成字符串(token)， 包含用户信息  实现单点登陆的一种方式
     组成部分: 头、 主体部分、 防伪标志\签名hash

  需要引入 jjwt 依赖  
    使用 JwtUtils 工具类 