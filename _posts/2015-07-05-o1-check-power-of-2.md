---
layout: post
title: "O(1)检测2的幂次--LintCode"
date: 2015-07-05 00:38:20
category: "LintCode"
tags: 位运算
author: tangmi
---
用 O(1) 时间检测整数 n 是否是 2 的幂次。

<!--break-->

#### 示例
    n=4，返回 true;
    n=5，返回 false.

#### 算法思路

    //TODO
    时间复杂度：O(1) 

#### 代码实现

    class Solution
    {
    public:
        /*
        * @param n: An integer
        * @return: True or false
        */
        bool checkPowerOf2(int n)
        {
            if(n > 0 && (n & n-1) == 0)
            {
                return true;
            }
            else
            {
                return false;
            }
        }
    };

